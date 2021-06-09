# Temp
![GitHub commit checks state](https://img.shields.io/github/checks-status/TovikMay/Temp_Ken/TovikMay?style=plastic)
![GitHub branch checks state](https://img.shields.io/github/checks-status/TovikMay/Temp_Ken/TovikMay?logo=Github&logoColor=%23F05032&style=flat-square)
![GitHub branch checks state](https://img.shields.io/github/checks-status/TovikMay/Temp_Ken/TovikMay?logo=Gitlab&logoColor=%23F050567&style=flat-square)

Feature: Is it Friday yet?
  Everybody wants to know when it's Friday

  Scenario: Sunday isn't Friday
    Given today is Sunday
    When I ask whether it's Friday yet
    Then I should be told "Nope"
