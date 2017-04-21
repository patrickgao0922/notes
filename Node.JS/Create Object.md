# Create Object

## Method 1

```javascript
ver person = {
	firstname: "",
	lastname: "",
	greet: function() {
	return this.firstname+ " " + this.lastname
	}
}

var john = Object.create(person)
john.firstname = "John"
john.lastname = "Doe"
```

## Method 2

```javascript

```