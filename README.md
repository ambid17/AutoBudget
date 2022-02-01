# AutoBudget
WPF app that helps with personal budgeting

Here I will take notes on the setup of the project for learning purposes.

Steps:

1. Create and clone git repo.
2. Create project in Visual Studio
  - Open VS 2019
  - Create a new project
  - Select "WPF Application" project template
  - Rename the project, set the Location to the cloned git repo
  - Set Target Framework to .NET 5.0
  
3. Install ModernWpf:  https://github.com/Kinnara/ModernWpf
 - In VS: Tools > Nuget Package Manager > Open Package Manager Console
 - Follow the rest of the steps at the link above

4. I tried building, got an error. I looke at the ModernWpf "issues", and found the solution: https://github.com/Kinnara/ModernWpf/issues/425
5. We can now build and run, and we get a decent looking app out of the box
