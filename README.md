# MI-AFP homework #08

 Homework to create simple *Debt Diary*

## Task

This time the task is up to you from scratch so you will learn how to make web app projects without any big limitations, strict tests, and given code. You are free to use any web framework you want (and possibly practice those technologies for semester or other project)! There are only few technical things you must follow and the topic:

1. The topic is **Debts Diary** = your application must be able to create, retrieve, update, delete, and list records of debt record. Each record consists at least of unique id, timestamp, amount of money, and from/to who debt is.
2. Database must be used to store the data, allowed types are: postgresql, mysql, mongodb, and sqlite (preferred). It is up to you what library you want to use.
3. There should be basic templates using `blaze-html` or `ginger`. Visual side is not graded but it is good practice to use some CSS framework...

Routes:

* `GET /` = summary page with list of people and amount of money in debt
* `GET /debts` = list of all debts (with ability to edit or delete one) with form to add new one
* `POST /debts` = create new record (then redirect to list)
* `DELETE /debts/<id>` = update existing record (then redirect to list)
* `PUT /debts/<id>` = update existing record (then redirect to list)
* (or/optional) `PATCH /debts/<id>` = update existing record (then redirect to list)

Optionally, you can test and document your application!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE)
file for more details.
