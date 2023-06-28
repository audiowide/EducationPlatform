# EducationPlatform
Next

<h3>Actions:</h3>

 - User
    - Sign In
    - Sign Up
    - Sign Out
    - Show Profile
        - Show Info
        - Show Started Courses with progress
        - Show Lower Courses
        - Show all comments
    - Update Profile
    - Delete Profile
 
 - Course
    - Show All Courses with filters, search and sorting(asc, desc)
    - Show One Course with titles and tasks
    - Show one task
        - Pagination 
        - 4 tasks types(text, video, test, code)
    - Create course
        - create title
            - create task
    - Admin panel
        - update info about course
        - update title
        - update task
        - move tasks, titles
        - delete title 
        - delete task
        - delete course
        - show all comments
        - show all reviews

<h3>Models:</h3>
    
    - User:
        Username 
        Email (unique)
        Password
        location
        description
        lower courses

        github_link
        gitlub_link
        figma_link

<hr>

    - Course:
        title
        description
        user 
        level
        base_knowledge
        time
    
<hr>

    - Title:
        Course
        Name
        Description

<hr>

    - Task:
        Title of course
        type of task (text, video, test, code)
        name of task
        __if text__:
            text
        __if code__:
            result
        _if video__:
            file
        __if test__:
            questions
        
<hr>

    - Question
        name of question
        descritption
        answer
        
        question1
        question2
        question3
        question4
