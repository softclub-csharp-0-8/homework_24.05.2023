## Assignment

## Task 1:

```mermaid
erDiagram
CATEGORIES ||--|{ QUOTES : has
    CATEGORIES {
        INT Id
        string CategoryName
    }
    QUOTES {
        INT Id
        string Author
        string QuoteText
        int CategoryId
    }
```

Functions.

- Learn the project from <a href="https://github.com/NurulloSulaymonov/DapperCrud" target="_blank">Last Practice</a>
- Use Clean Arcitecture design (Domain,Infrastructure,Console).
- Methods to implement 
  - Add & edit Quote and Category
  - Get list of Qutoes including categoryName
  - Get all quotes by category (send category id and get all quotes). 
  - Get a random quote. 
- Learn the Dapper from <a href="https://www.learndapper.com/dapper-query" target="_blank">Dapper documentation</a>

Requirements:
- Create a new repository in your project. Name it with `homework_25.05.2023`
- Add gitignore into your project (`dotnet new gitignore`)

On average, this task can be completed in 2-3 hours, but you are welcome to spend more time on it to submit a better quality code.
<br /> Make sure to send it until **25.05.2023T18:00**.
<br /> Happy Coding 😊
