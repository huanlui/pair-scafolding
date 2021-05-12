# Pairing exercise

This is the scaffolding for a pairing exercise example.

Below you can find the description of a user story where the requirements are defined. 

## US-1452: Validate user form

### Context 

In our application, there is a form to register as a user, but the input is not being validated. This US consists on adding this validation

### Acceptance Criteria

- Given that the user does not fill the name, then the validation should not pass. 
- Given a user that is less than 18 years old, then the validation should not pass. 
- Given a user that has less than two hobbies, then the validation should not pass. 
- Given a user that has repeated hobbies, then the validation should not pass. 

### Technical Details

The user input is available on the class [UserDetails](/src/main/java/org/huanlui/pair/scaffolding/domain/UserDetails.java).
