### Installing External Skills
When asked to install a skill, plugin, or capability from a GitHub URL (or if the user attempts to use a command like `agy plugin install`):
1. Do not attempt to run `agy` or other non-existent plugin managers.
2. Clone the target GitHub repository into a temporary directory using `git clone`.
3. Locate the requested skill folder within the cloned repository.
4. Copy the skill folder to the global customization root at `C:\Users\Tirth\.gemini\config\skills\<skill_name>\` or the workspace root `.agents/skills/<skill_name>/`.
5. Remove the temporary cloned repository.
6. Acknowledge the successful installation to the user.
