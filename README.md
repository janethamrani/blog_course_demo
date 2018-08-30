# Planning our application
    1. Answer Questions
        - What are we building?
        - Who are we building it for?
        - What features do we need to have?
            - Posts
              - Create / Edit / destroy
              - markdown
              - Syntax Highlighting
              - Comments (Disquis)
            - Projects
              - Create / Edit / destroy
            - contact
              - Contact form
              - Sendgrid
              - User (Devise)
    2. User Stories
    3. Model our data
    4. Think through the pages we need in our app

## Questions
    1. What are we building? We are building a personal site. A place where we can blog, share examples of our work, and have people contact us
    2. Who are we building it for? We are building it for ourselves, but we are also building it for the community. Sharing what we are learning by blogging is a great way to teach others while also teaching ourselves. Show potential employers that we know what we are doing.
    3. What features do we want to have?
## User Stories
    As a blank, I want to be able to blank, so that blank.
        - As a user, I want to be able to create posts so that I can share what I am learning on my blog.
        - As a user, I want to be able to edit and destroy posts, so that I can manage my blog
        - As a user, I want to be able to write posts in markdown format so that it's easy for me to write posts
        - As a user, I want to be able to highlight the various syntax of code blocks that I share on my blog
        - As a user, I want to be able to show the visitors and potential employers examples of my work, or stuff I've built
        - As a user, I want to have visitors be able to leave comments on my posts

## Modeling Our data
    **posts**
      title::string
      content::string
    **project**
      title::string
      description::text
      link::string

## Think through the pages we need in our application
    - Home
    - Posts#index
    - Posts#show
    - Projects#index
    - Projects#show
    - Contact
