
# Ruby on Rails - Project Management App


### What are we building? 

The goal of the app is to be a home for any amount of projects(*think [Basecamp](https://basecamp.com) but much more stripped down*). A project lives within a team and can have as many users as necessary. A user can only belong to one team at a time (*this is a small side-effect of the [Devise gem](https://github.com/plataformatec/devise). Ultimately, we'd want to extend this to allow a single user to belong to multiple teams.*)

The app will have 3 overlying models/relationships to tie together each other as we press forward but I'll outline the "wants" below:

1. A User can create a project if they belong to a team.
2. Creating a team assigns both your own account plus those you invite to a team.
3. Projects require a team in order to be created.