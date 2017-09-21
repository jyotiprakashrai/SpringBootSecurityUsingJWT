# SpringBootSecurityUsingJWT
Spring Security using JWT(Json web token) in Spring Boot Application

#########################################################################################

To test this demo 

Step-1: Hit the token generation method using POSTMAN(Post method)

http://localhost:8080/token

With Body having following "raw"
{
"userName":"Jyoti",
"id": 123,
"role":"admin"
}
along with "JSON(application/json)"

In response it will return token

for example(add prefix 'Token ' for this demo)
Token eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJKeW90aSIsInVz
ZXJJZCI6IjEyMyIsInJvbGUiOiJhZG1pbiJ9.OYT2dAc5q4PEEj15I_zJ-wy0Tt8bYn_Y_YERjeakq5G5l1UMfs0XOznHLMtnRyAcpdehd8LtJMqVV--WatPQow

Step-2: Hit the normal web method

 http://localhost:8080/rest/hello
 
 With "Headers"
 
Authorisation:....(token)


