# Project for interview Mobile Engineer

- ### Requirements

  - ### Login Page

    - ##### Features
      - Input username and password to goto "Album Page".
    - ##### Components
      - Text
        - Display text "ONE OK ROCK Album".
        - Use Kanit-Bold as font-family.
      - Username TextField
        - Validate user input >= 10 character
        - Display "Pls enter username more than 9 character" when user enter username less than 10 character
      - Password TextField
        - Validate user input >= 7 character
        - Display "Pls enter password more than 6 character" when user enter password less than 7 character
      - Login Button
        - Enable when user input correct format username and password.
        - Disable when user input invalid format username and password.
        - Tap to goto "Album Page".

  - ### Album Page
    - ##### Features
      - Display all of album card by load json data (assets/json).
      - User can view all of album card by scroll from the top to the bottom of page.
    - ##### Components
      - AppBar
        - Display text "Album List"
      - Album Card
        - Display album's image.
        - Display album's name with Kanit-Regular as font family.
        - Display album's year with Kanit-Italic as font family.
        - You can see example image inside assets/example/album-card.

- ### NOTE
  - Freely to design your component.
  - Freely to add all features that you think.
  - Freely to choose all pattern design.
    - eg. MVVM, MVC, Clean architecture and other.
  - Just show we everything you can do !!! Fighting <3.
