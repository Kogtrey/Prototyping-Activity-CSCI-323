# Names:
- Kody Neill
- Saan Rice
- Catey Meador
- Jan Roddy
- Brandon ?
# Prototyping-Activity-CSCI-323
Activity for prototyping a children's reading app.
Note from the authors: Please avoid "Creature Freep"

## Functional Requirements

1. bookmark 
2. progress/ reward system 
3. login capability 
4. create account 
5. search function 
6. highlighting function 
7. pause/ play change speed 
8. skip forward buttons 
9. help function 


## Non-Functional Requirements
1. intuitive design
2. download capability 
3. cross operating system 
4. network connection 
5. runs on tablets 


## User Testing Notes 
###### Positive 
- genres 
- intuitive design 
-
###### Negative 
- "blacklist" -too intense let’s try “blocked books” 
- menu popup sidebar -what does it look like
- fast forward buttons are confusing 
- need a user tutorial 

## User Stories
1. Johnny 13 year old boy, goal mess with parents credit card information
    1. sign in under his account 
    2. go to account information 
    3. navigate to payment info 
    4.  he won’t know that password 
2. Emily 7 wants to her favorite book “Rainbow for Puppies” 
    1. her parent logs her in and hands her tablet 
    2. finds book she wants to read based on cover picture 
    3. chooses read myself button 
    4. reads book pages and continues on to next page 
    5. see’s her progress report
    6. reads it again 
3. Cindy, parent of Emily, restrict books for children
    1. login to account
    2. navigate to menu 
    3. go to account information
    4. choose parental settings 
    5. edit blocked books 
    6. search for “Rainbows for Puppies” 
    7. click block this book (+)
4. Teacher, Caroline, teaches Kindergarten, use as tool for her classroom to read a book to her class
    1. create account 
    2. login to account
    3. pick book
    4. go through tutorial 
    
5. Jim, 10 yrs, english as a second language learner, wants to practice english reading, record his reading with microphone and check pronunciation 
    1. He already has an account and signs in 
    2. He selects a book 
    3.  read to the tablet “read to you” 
    4.  he needs to take a break and pause to do something 
    5. a few minutes later he gets back at it 
    6. finishes, sees report and practices what he missed
	
## Test Plan: Login

#### input: 
1. username
2. password 
3. button clicks

#### tests:
1. Test to see if username is captured
2. Test to see if password is captured
3. Test to see if correct combination of password and username is recognized and allows login
4. Test to see if wrong information prevents login to account

#### output: 
1. Ok or error message if the login works or does not work 


## Test Plan: Search and Filter Feature

#### input: 
1. genre
2. age group
3. title
4. author

#### tests:
1. Test to see if genre filters books correctly
2. Test to see if age group filters books correctly
3. Test to see if title filters books correctly
4. Test to see if author filters books correctly
5. Test to see if blocked titles are filtered out

#### output: 
1. Ok or error message if the metadata matches the filters


## Test Plan: Parental Settings

#### input:
1. password

#### tests:
1. Test if login is allowed with correct password
2. Test if login is allowed with incorrect password

#### output:
1. OK or error message indicating incorrect password


## Test Plan: Control Bar Functionality

#### input:
1. Test input for play button
2. Test input for pause button
3. Test input for forward button
4. Test input for back button
5. Test input for Read to me button
6. Test input for Read myself
7. Test input from speed slider

#### tests:
1. Test if play button starts playback
2. Test if pause button stops playback
3. Test if forward button moves forward a line
4. Test if back button moves backward a line
5. Test is speed slider adjusts speed up and down
6. Test is read myself button replaces play button with record button
7. Test if read to me button replaces record button with play button 

#### output:
1. OK or error message indicating if button acted incorrectly

