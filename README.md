# hibernate-04-configuring-collections-and-adding-primary-keys
Persisting Collection Value Types with primary key in entity class

Postman Request and Response details

- **Method :** POST
- **URL :** 
- **Request Body : ** - 
```
{
	"employeeId": 0,
	"employeeName":"Chandru R",
	"department":"Development",
	"gender": "Male",
	"addressList": [{
		"streetName":"Sankara Madam Street",
		"city":"Emakandanur",
		"state": "Tamil Nadu",
		"country": "India"
	},
	{
		"streetName":"Sanjeevi Street",
		"city":"Chennai",
		"state": "Tamil Nadu",
		"country": "India"
		
	}]
}
```
- **Response Body : **
```
{
    "data": {
        "employeeId": 1,
        "employeeName": "Chandru R",
        "gender": "Male",
        "department": "Development",
        "addressList": [
            {
                "streetName": "Sankara Madam Street",
                "city": "Emakandanur",
                "state": "Tamil Nadu",
                "country": "India"
            },
            {
                "streetName": "Sanjeevi Street",
                "city": "Chennai",
                "state": "Tamil Nadu",
                "country": "India"
            }
        ]
    },
    "message": "Employee saved successfully",
    "exception": false,
    "success": true
}
```

