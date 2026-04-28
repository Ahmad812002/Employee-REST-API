# Employee REST API

A clean and well-structured RESTful API that serves employee data.  
Built with C# and ASP.NET Web API, it follows REST principles and 
returns structured JSON responses.

## Endpoints
| Method | Endpoint                         | Description                                                                                                    |
|--------|--------------------------------- |----------------------------------------------------------------------------------------------------------------|
| GET    | /api/employees                   | Get all employees                                                                                              |
| GET    | /api/employees/{national_num}    | Get the highest salary, calculate the average salary, and classify each employee as above or below the average.|
| GET    | /api/employee_info/{national_num}| Get employee by national number                                                                                |                                                                                        |

## Tech Stack
| Layer      | Technology        |
|------------|-------------------|
| Language   | C#                |
| Framework  | ASP.NET Web API   |
| IDE        | Visual Studio     |
| Format     | JSON              |

## Getting Started
1. Clone the repository
2. Open in Visual Studio
3. Update the connection string in appsettings.json
4. Run the project
5. use any API platform to get response from endpoints (Postman)

## Example Response
{
    "highest": 8000.0,
    "avg": 3087.5,
    "status": "Green"
}
