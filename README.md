# Coding Best Practices

This is a list of best practices for writing code. Like with many things in life, there will be exceptions to the rules. Therefore, this list is not meant to be followed to the letter. It is meant to be a guideline which helps us write high quality code. Feel free to contribute by creating a Pull Request or an Issue!

- KISS: Keep It Simple, Stupid
- Prevent code duplication
- Leave the campground cleaner than you found it
- Prioritize readability over performance
- Prefer Object Oriented code over Procedural code
- Stand on the shoulders of giants: do not reinvent the wheel
- Only use interfaces when there is more than 1 implementation
- Prefer typed code over untyped code
- Prefer Strong typing over Weak typing
- Prefer Static typing over Dynamic typing
- Use automatic code formatting
- Follow the Twelve-Factor app methodology
- Do not change code for automated testing purposes: writing tests is not a valid reason for change
- Do not use Exceptions for control flow
- Strive for Continuous Delivery
- Strive for Continuous Deployment
- Stick to a development workflow that works for you and your stakeholders
- Use constants instead of hardcoded strings
- Use static functions when possible
- Place 1 class in 1 file
- Keep functions shorter than 10 lines
- Keep classes shorter than 100 lines
- Adhere to a coding standard 
- Have your CI tool perform linting checks automatically
- Do not use comments: easily readable code does not need comments
- If you do need comments, only explain why something was done, the code tells you how it was done
- Write code that your IDE can follow
- Do not use magic methods
- Validate input
- Encode output
- Use existing Software Design Patterns to solve common problems
- Apply the SOLID principles if it prevents code from becoming hard to reuse, change or understand
- Prevent gold plating: do not apply coding best practices at the cost of simplicity to allow for flexibility in directions that are unlikely
- Prevent gold plating: do not create more features than strictly necessary
- Create wrappers around external services or dependencies in order to decouple them from your application
- Use meaningful names for everything you name like classes, functions and variables

**Version control**
- Use version control tools
- Prevent Long-lived feature branches. Short-lived feature branches can be good
- Use one monorepo: prefer fewer repositories over more


