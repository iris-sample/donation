# Donation
A very simple example of using the stripe API along with golang.

It is a simple form that accepts credit card details and then creates the
stripe token and sends it to the backend when the form is submitted. Then it processes
the charge and send the user back to the index with success=t or success=f

To setup copy the conf.example.toml to conf.toml and put your stripe keys in. Then I have included
a make file if you have make installed. If not run

```go
qtc -dir ./view
go build -v
```
