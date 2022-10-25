# AspNetCoreTotpSample

To run project:
* In Package Manager Console: dotnet tool install --global dotnet-ef (if not installed previously)
* In Package Manager Console: dotnet ef database update
* Run project

To use TOTP:
* Run project
* Register account (if not registered)
* Log in
* Go to your Profile
* Go to Two-factor authentication
* Set up authenticator app
* Log out
* Log in with TOTP

Resources used:
* https://learn.microsoft.com/en-us/aspnet/core/security/authentication/identity-enable-qrcodes?view=aspnetcore-6.0
* https://davidshimjs.github.io/qrcodejs/
