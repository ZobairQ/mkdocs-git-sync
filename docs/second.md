# How to modify the current git sync.

- Add Environment variables for username, email and SSH key inside your dockerfile 
- Modify the main.go to load these new variables and set them as global config on git
- Then everything should be good.