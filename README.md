<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
   <h2> que-1 Create a database , give it name like "Human-Resource". Create a collection inside this named "employee".</h2> <br>
    <h4>test> show dbs
        admin     40.00 KiB
        client    48.00 KiB
        config    60.00 KiB
        database  72.00 KiB
        local     40.00 KiB</h4>

        <h4>test> use Human_Resource
            switched to db Human_Resource</h4>

<h2>que-2 -Query the collection ""employee"" and list all the documents <br></h2>
  <pre> Human_Resource> db.employee.insertMany([{
    ...
    ...   "firstName": "John",
    ...   "lastName": "Doe",
    ...   "salary": "25000",
    ...   "department": "HR",
    ...   "lastCompany": "X",
    ...   "lastSalary": "10000",
    ...   "overallExp": "2",
    ...   "contactInfo": "1234567890",
    ...   "yearGrad": "2016",
    ...   "gradStream": "CSE"
    ... },{
    ...
    ...   "firstName": "Rohan",
    ...   "lastName": "Jame",
    ...   "salary": "30000",
    ...   "department": "Technical",
    ...   "lastCompany": "Y",
    ...   "lastSalary": "15000",
    ...   "overallExp": "1",
    ...   "contactInfo": "1234567860",
    ...   "yearGrad": "2015",
    ...   "gradStream": "CSE"
    ... },{
    ...
    ...   "firstName": "Jame",
    ...   "lastName": "Doe",
    ...   "salary": "35000",
    ...   "department": "Accounts",
    ...   "lastCompany": "Z",
    ...   "lastSalary": "20000",
    ...   "overallExp": "1",
    ...   "contactInfo": "123567890",
    ...   "yearGrad": "2019",
    ...   "gradStream": "ECE"
    ... },{
    ...
    ...   "firstName": "Sao",
    ...   "lastName": "Avika",
    ...   "salary": "30000",
    ...   "department": "Sales",
    ...   "lastCompany": "Y",
    ...   "lastSalary": "15000",
    ...   "overallExp": "2",
    ...   "contactInfo": "1234567860",
    ...   "yearGrad": "2015",
    ...   "gradStream": "CSE"
    ... },{
    ...
    ...   "firstName": "Jame",
    ...   "lastName": "roh",
    ...   "salary": "35000",
    ...   "department": "Accounts",
    ...   "lastCompany": "Z",
    ...   "lastSalary": "15000",
    ...   "overallExp": "2",
    ...   "contactInfo": "123567890",
    ...   "yearGrad": "2019",
    ...   "gradStream": "EEE"
    ... },{
    ...
    ...   "firstName": "Rohan",
    ...   "lastName": "Jame",
    ...   "salary": "30000",
    ...   "department": "Technical",
    ...   "lastCompany": "Y",
    ...   "lastSalary": "15000",
    ...   "overallExp": "1",
    ...   "contactInfo": "1234567860",
    ...   "yearGrad": "2015",
    ...   "gradStream": "CSE"
    ... },{
    ...
    ...   "firstName": "Jame",
    ...   "lastName": "Doe",
    ...   "salary": "35000",
    ...   "department": "Accounts",
    ...   "lastCompany": "Z",
    ...   "lastSalary": "20000",
    ...   "overallExp": "1",
    ...   "contactInfo": "123567890",
    ...   "yearGrad": "2019",
    ...   "gradStream": "ECE"
    ... },{
    ...
    ...   "firstName": "Sao",
    ...   "lastName": "Avika",
    ...   "salary": "30000",
    ...   "department": "Sales",
    ...   "lastCompany": "Y",
    ...   "lastSalary": "15000",
    ...   "overallExp": "2",
    ...   "contactInfo": "1234567860",
    ...   "yearGrad": "2015",
    ...   "gradStream": "CSE"
    ... },{
    ...
    ...   "firstName": "Jame",
    ...   "lastName": "Doe",
    ...   "salary": "35000",
    ...   "department": "Accounts",
    ...   "lastCompany": "Z",
    ...   "lastSalary": "15000",
    ...   "overallExp": "2",
    ...   "contactInfo": "123567890",
    ...   "yearGrad": "2019",
    ...   "gradStream": "EEE"
    ... },{
    ...
    ...   "firstName": "Rohan",
    ...   "lastName": "Jame",
    ...   "salary": "30000",
    ...   "department": "Technical",
    ...   "lastCompany": "Y",
    ...   "lastSalary": "15000",
    ...   "overallExp": "1",
    ...   "contactInfo": "1234567860",
    ...   "yearGrad": "2015",
    ...   "gradStream": "CSE"
    ... },{
    ...
    ...   "firstName": "Jame",
    ...   "lastName": "Doe",
    ...   "salary": "35000",
    ...   "department": "Accounts",
    ...   "lastCompany": "Z",
    ...   "lastSalary": "20000",
    ...   "overallExp": "1",
    ...   "contactInfo": "123567890",
    ...   "yearGrad": "2019",
    ...   "gradStream": "ECE"
    ... },{
    ...
    ...   "firstName": "Sao",
    ...   "lastName": "Avika",
    ...   "salary": "30000",
    ...   "department": "Sales",
    ...   "lastCompany": "Y",
    ...   "lastSalary": "15000",
    ...   "overallExp": "2",
    ...   "contactInfo": "1234567860",
    ...   "yearGrad": "2015",
    ...   "gradStream": "CSE"
    ... },{
    ...
    ...   "firstName": "Jame",
    ...   "lastName": "Doe",
    ...   "salary": "35000",
    ...   "department": "Accounts",
    ...   "lastCompany": "Z",
    ...   "lastSalary": "15000",
    ...   "overallExp": "2",
    ...   "contactInfo": "123567890",
    ...   "yearGrad": "2019",
    ...   "gradStream": "EEE"
    ... }])
    {
      acknowledged: true,
      insertedIds: {
        '0': ObjectId("63837398fa7a20f4f6e640d2"),
        '1': ObjectId("63837398fa7a20f4f6e640d3"),
        '2': ObjectId("63837398fa7a20f4f6e640d4"),
        '3': ObjectId("63837398fa7a20f4f6e640d5"),
        '4': ObjectId("63837398fa7a20f4f6e640d6"),
        '5': ObjectId("63837398fa7a20f4f6e640d7"),
        '6': ObjectId("63837398fa7a20f4f6e640d8"),
        '7': ObjectId("63837398fa7a20f4f6e640d9"),
        '8': ObjectId("63837398fa7a20f4f6e640da"),
        '9': ObjectId("63837398fa7a20f4f6e640db"),
        '10': ObjectId("63837398fa7a20f4f6e640dc"),
        '11': ObjectId("63837398fa7a20f4f6e640dd"),
        '12': ObjectId("63837398fa7a20f4f6e640de")
      }
    }
</pre>
<h2>que 3--Query the collection ""employee"" and list the employees who are having salary more than 30000 <br></h2>
     <pre>Human_Resource> db.employee.find({salary:{$gt:"30000"}})
    [
      {
        _id: ObjectId("63837398fa7a20f4f6e640d4"),
        firstName: 'Jame',
        lastName: 'Doe',
        salary: '35000',
        department: 'Accounts',
        lastCompany: 'Z',
        lastSalary: '20000',
        overallExp: '1',
        contactInfo: '123567890',
        yearGrad: '2019',
        gradStream: 'ECE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640d6"),
        firstName: 'Jame',
        lastName: 'roh',
        salary: '35000',
        department: 'Accounts',
        lastCompany: 'Z',
        lastSalary: '15000',
        overallExp: '2',
        contactInfo: '123567890',
        yearGrad: '2019',
        gradStream: 'EEE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640d8"),
        firstName: 'Jame',
        lastName: 'Doe',
        salary: '35000',
        department: 'Accounts',
        lastCompany: 'Z',
        lastSalary: '20000',
        overallExp: '1',
        contactInfo: '123567890',
        yearGrad: '2019',
        gradStream: 'ECE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640da"),
        firstName: 'Jame',
        lastName: 'Doe',
        salary: '35000',
        department: 'Accounts',
        lastCompany: 'Z',
        lastSalary: '15000',
        overallExp: '2',
        contactInfo: '123567890',
        yearGrad: '2019',
        gradStream: 'EEE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640dc"),
        firstName: 'Jame',
        lastName: 'Doe',
        salary: '35000',
        department: 'Accounts',
        lastCompany: 'Z',
        lastSalary: '20000',
        overallExp: '1',
        contactInfo: '123567890',
        yearGrad: '2019',
        gradStream: 'ECE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640de"),
        firstName: 'Jame',
        lastName: 'Doe',
        salary: '35000',
        department: 'Accounts',
        lastCompany: 'Z',
        lastSalary: '15000',
        overallExp: '2',
        contactInfo: '123567890',
        yearGrad: '2019',
        gradStream: 'EEE'
      }
    ]
    
</pre> 
<h2>que-4 Query the collection ""employee"" and list the employees who are having experience more than 2 years. <br></h2>
   <pre> Human_Resource> db.employee.find({overallExp:{$gte:"2"}})
    [
      {
        _id: ObjectId("63837398fa7a20f4f6e640d2"),
        firstName: 'John',
        lastName: 'Doe',
        salary: '25000',
        department: 'HR',
        lastCompany: 'X',
        lastSalary: '10000',
        overallExp: '2',
        contactInfo: '1234567890',
        yearGrad: '2016',
        gradStream: 'CSE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640d5"),
        firstName: 'Sao',
        lastName: 'Avika',
        salary: '30000',
        department: 'Sales',
        lastCompany: 'Y',
        lastSalary: '15000',
        overallExp: '2',
        contactInfo: '1234567860',
        yearGrad: '2015',
        gradStream: 'CSE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640d6"),
        firstName: 'Jame',
        lastName: 'roh',
        salary: '35000',
        department: 'Accounts',
        lastCompany: 'Z',
        lastSalary: '15000',
        overallExp: '2',
        contactInfo: '123567890',
        yearGrad: '2019',
        gradStream: 'EEE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640d9"),
        firstName: 'Sao',
        lastName: 'Avika',
        salary: '30000',
        department: 'Sales',
        lastCompany: 'Y',
        lastSalary: '15000',
        overallExp: '2',
        contactInfo: '1234567860',
        yearGrad: '2015',
        gradStream: 'CSE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640da"),
        firstName: 'Jame',
        lastName: 'Doe',
        salary: '35000',
        department: 'Accounts',
        lastCompany: 'Z',
        lastSalary: '15000',
        overallExp: '2',
        contactInfo: '123567890',
        yearGrad: '2019',
        gradStream: 'EEE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640dd"),
        firstName: 'Sao',
        lastName: 'Avika',
        salary: '30000',
        department: 'Sales',
        lastCompany: 'Y',
        lastSalary: '15000',
        overallExp: '2',
        contactInfo: '1234567860',
        yearGrad: '2015',
        gradStream: 'CSE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640de"),
        firstName: 'Jame',
        lastName: 'Doe',
        salary: '35000',
        department: 'Accounts',
        lastCompany: 'Z',
        lastSalary: '15000',
        overallExp: '2',
        contactInfo: '123567890',
        yearGrad: '2019',
        gradStream: 'EEE'
      }
    ]
</pre>
    
    
    <h2>que-5 -Query the collection ""employee"" and list the employees who are graduated after 2015 and having experience more than 1 year <br></h2>
    <pre> Human_Resource> db.employee.find({yearGrad:{$gt:"2015"},overallExp:{$gt:"1"}})
    [
      {
        _id: ObjectId("63837398fa7a20f4f6e640d2"),
        firstName: 'John',
        lastName: 'Doe',
        salary: '25000',
        department: 'HR',
        lastCompany: 'X',
        lastSalary: '10000',
        overallExp: '2',
        contactInfo: '1234567890',
        yearGrad: '2016',
        gradStream: 'CSE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640d6"),
        firstName: 'Jame',
        lastName: 'roh',
        salary: '35000',
        department: 'Accounts',
        lastCompany: 'Z',
        lastSalary: '15000',
        overallExp: '2',
        contactInfo: '123567890',
        yearGrad: '2019',
        gradStream: 'EEE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640da"),
        firstName: 'Jame',
        lastName: 'Doe',
        salary: '35000',
        department: 'Accounts',
        lastCompany: 'Z',
        lastSalary: '15000',
        overallExp: '2',
        contactInfo: '123567890',
        yearGrad: '2019',
        gradStream: 'EEE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640de"),
        firstName: 'Jame',
        lastName: 'Doe',
        salary: '35000',
        department: 'Accounts',
        lastCompany: 'Z',
        lastSalary: '15000',
        overallExp: '2',
        contactInfo: '123567890',
        yearGrad: '2019',
        gradStream: 'EEE'
      }
    ]
</pre>
<h2>que-6 Query the collection ""employee"" and update the salary of the employee whose salary is greater than 70000 to 65000. <br></h2>
    
   <pre> Human_Resource> db.employee.updateMany({salary:{$gt:"70000"}},{$set:{salary:"65000"}})
    {
      acknowledged: true,
      insertedId: null,
      matchedCount: 0,
      modifiedCount: 0,
      upsertedCount: 0
    }
    
</pre>
<h2>que-7 -Delete all the documents from ""employee"" where last company is Y"</h2>
    
   <pre> Human_Resource> db.employee.deleteMany({lastCompany:"Y"})
    { acknowledged: true, deletedCount: 6 }
    
</pre>
<pre> 
    
    Human_Resource> db.employee.find().pretty()
    [
      { _id: ObjectId("63837092fa7a20f4f6e640d1"), name: 'pooja' },
      {
        _id: ObjectId("63837398fa7a20f4f6e640d2"),
        firstName: 'John',
        lastName: 'Doe',
        salary: '25000',
        department: 'HR',
        lastCompany: 'X',
        lastSalary: '10000',
        overallExp: '2',
        contactInfo: '1234567890',
        yearGrad: '2016',
        gradStream: 'CSE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640d4"),
        firstName: 'Jame',
        lastName: 'Doe',
        salary: '35000',
        department: 'Accounts',
        lastCompany: 'Z',
        lastSalary: '20000',
        overallExp: '1',
        contactInfo: '123567890',
        yearGrad: '2019',
        gradStream: 'ECE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640d6"),
        firstName: 'Jame',
        lastName: 'roh',
        salary: '35000',
        department: 'Accounts',
        lastCompany: 'Z',
        lastSalary: '15000',
        overallExp: '2',
        contactInfo: '123567890',
        yearGrad: '2019',
        gradStream: 'EEE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640d8"),
        firstName: 'Jame',
        lastName: 'Doe',
        salary: '35000',
        department: 'Accounts',
        lastCompany: 'Z',
        lastSalary: '20000',
        overallExp: '1',
        contactInfo: '123567890',
        yearGrad: '2019',
        gradStream: 'ECE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640da"),
        firstName: 'Jame',
        lastName: 'Doe',
        salary: '35000',
        department: 'Accounts',
        lastCompany: 'Z',
        lastSalary: '15000',
        overallExp: '2',
        contactInfo: '123567890',
        yearGrad: '2019',
        gradStream: 'EEE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640dc"),
        firstName: 'Jame',
        lastName: 'Doe',
        salary: '35000',
        department: 'Accounts',
        lastCompany: 'Z',
        lastSalary: '20000',
        overallExp: '1',
        contactInfo: '123567890',
        yearGrad: '2019',
        gradStream: 'ECE'
      },
      {
        _id: ObjectId("63837398fa7a20f4f6e640de"),
        firstName: 'Jame',
        lastName: 'Doe',
        salary: '35000',
        department: 'Accounts',
        lastCompany: 'Z',
        lastSalary: '15000',
        overallExp: '2',
        contactInfo: '123567890',
        yearGrad: '2019',
        gradStream: 'EEE'
      }
    ]
</pre>
</body>
</html>
