# Java-Quiz-Generator

## Problem Statement

Develop a tool that will enable one to randomly generate a quiz test
questionnaire containing the specified number of questions from the question bank. The question bank
and other related data need to be stored in a file/database or any other persistent structure as per the
convenience. If it is a file, the system should ensure that the file exits and the path is specified. Or else a
file is created with the specified name and stored in default location. Appropriate exception handling
mechanism should be taken care of wherever required in the application. There should be options for
separate question bank for separate subjects. The user should have the option of selecting the subject for
which the question bank is to be made or the questionnaire is to be generated.

Expected Functionalities:

Insert: The user should be able to insert a new question. There has to be an option to select the type of
question that the user wants to insert (MCQ OR true/false OR Fill-in the blanks). If the type is multiple
choice question, then the system should ask the user to write the question and the options in separate
spaces. There should be an option to enter the answer for that question. A submit button will enter the
question into the question bank. If it is a fill in the blanks question, then there should be only two spaces
one for the question and the other for the answer. Do the appropriate thing for True/False type.

Modify: This functionality will let the user to modify any question, its options, and/or its answer.

Delete: This functionality will let the user delete any particular question.

Generate Test: This functionality will let the user to view either the questions set or the solution set. This
functionality will ask the user to enter the number of questions to view. Supposing the user enters 10,
then 10 questions should be randomly generated and displayed on the screen. It should also let the user
export the questions in txt/word format. While generating the questions randomly the system should
ensure that the same question is not repeated. The same should happen if the user wants to generate the
solution set for the specified number of questions.

Also design a GUI for the above project. Appropriate links
should be provided to navigate from one option to another. The project should be deployable.
