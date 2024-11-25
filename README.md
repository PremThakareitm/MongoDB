  MongoDB Notes.

    // db.students.insertMany([
    //     {First_Name : "Prem",
    //     Last_Name : "Thakare",
    //     date_of_birth: "June 04, 2005",
    //     grade: 8.63
    //     },
    //         {First_Name : "Sakshi",
    //     Last_Name : "Thakare",
    //     dob: new Date("January 12, 2002")
    //         } 
    // ])

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

    // db.students.insertOne({
    //         First_Name: "Prem",
    //         Last_Name: "Thakare"
    // })
    
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

    // db.students.insertMany([{
    //         First_Name: "Prem",
    //         designation: "Manager",
    //         dob: "June 04, 2005"
    // },
    //     {
    //         First_Name: "Sakshi",
    //         designation: "HR",
    //         dob: "January 12, 2002"
    //         },
    //     {
    //        Firs_Name:  "Ranjana",
    //         designation: "Head",
    //         dob: "December 12, 1980"
    //     }
    //     ])

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

    // db.students.insertMany([
    //     {Eid:01, First_Name: "Prem",designation: "Manager"},
    //     {Eid:02,First_Name: "Sakshi",designation: "HR"},
    //     {Eid:03,Firs_Name:  "Ranjana",designation: "Head"}
    //     ])
    
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

    // db.collection.insertMany([
    //     {
    //         household_item: "journal",
    //         household_qty: 2590,
    //         size: {h: 14, w: 21, uom: 'cm'},
    //         present_status: 'A'
    //     },
    //     {
    //         household_item: "notebook",
    //         household_qty: 550,
    //         size: {h: 8.5, w: 11, uom: 'in'},
    //         present_status: 'A'
    //     },
    //     {
    //         household_item: "paper",
    //         household_qty: 100,
    //         size: {h: 8.5, w: 11, uom: 'in'},
    //         present_status: 'D'
    //     },
    //     {
    //         household_item: "planner",
    //         household_qty: 75,
    //         size: {h: 22.85, w: 30, uom: 'cm'},
    //         present_status: 'D'
    //     },
    //     {
    //         household_item: "postcard",
    //         household_qty: 45,
    //         size: {h: 10, w: 15.25, uom: 'cm'},
    //         present_status: 'A'
    //     }
    // ])

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

    // db.students.insert(
    //     {
    //         FirstName: "Prem",
    //         LastName: "Thakare",
    //         dateofbirth: "June 04,2005",
    //         grade: "SYBetch"
    //     }
    // );
    
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

    // db.students.insert(
    //     {
    //         FirstName: "Prem",
    //         LastName: "Thakare",
    //         dateofbirth: "June 04,2005",
    //         grade: 8.10824591
    //     },
    //     {
    //         FirstName: "Sakshi",
    //         LastName: "Thakare",
    //         dateofbirth: new Date ( "January 12,2002")
    //     }
    // );

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

    // db.students.insertMany([
    //     {
    //         ename: "Prem",
    //         designation: "Manager",
    //         dob: "June 04,2005"
    //     },
    //     {
    //         ename: "Json",
    //         designation: "HR",
    //         dob: new Date ("July 12,2002"),
    //         pay_scale: 10
    //     },
    //     {
    //         ename: "Rose",
    //         designation: "BI Analytics"
    //     }
    // ]);
    // show dbs;
    // show collections;

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

    // db.employees.insertMany([
    //         {empid:01, name: "Prem", dept: "Professor"}
    //         {empid:02, name: "Sakshi", dept: "HR"}
    //         {empid:03, name: "Jensen", dept: "Head of Programming"}
    
    // ]);
    // show dbs;
    // show collections;

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

     // db.collection.insertMany([
     //        {
     //            household_item: "journalentry",
     //            household_qty: 2590.1,
     //            size: {h: 14, w: 21, uom: 'cm'},
     //            present_status: 'A'
     //        },
     //        {
     //            household_item: "notebook",
     //            household_qty: 550.34,
     //            size: {h: 8.5, w: 11, uom: 'in'},
     //            present_status: 'A'
     //        },
     //        {
     //            household_item: "paper",
     //            household_qty: 100.789,
     //            size: {h: 85, w: 11, uom: 'in'},
     //            present_status: 'D'
     //        },
     //        {
     //            household_item: "planner",
     //            household_qty: 75.67,
     //            size: {h: 22.85, w: 30, uom: 'cm'},
     //            present_status: 'D'
     //        },
     //        {
     //            household_item: "postcard",
     //            household_qty: 45,
     //            size: {h: 10, w: 15.25, uom: 'cm'},
     //            present_status: 'A'
     //        }
     //    ])

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

    // db.students.insertMany([
    //     {
    //         first_name: "Prem",
    //         last_name:"Thakare",
    //         department: "Btech",
    //         address: {
    //             Type:"Home",
    //             Numbe: 91566201123,
    //         }
    //     }
    // ])

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

    // db.employees.insertMany{[
    //     {id:111,ename:"Prem",gender:"M"},
    //     {id:222,ename:"Anil",gender:"M"},
    //     {id:333,ename:"Ranjana",gender:"F"},
    //     {id:444,ename:"Sakshi",gender:"F"},
    //     {id:555,ename:"Piyush",gender:"M"},
    //     {id:666,ename:"Romil",gender:"M"},
    //     {id:777,ename:"Probod",gender:"M"},
    //     {id:888,ename:"Patil",gender:"M"},
    //     {id:999,ename:"Mahajan",gender:"M"},
    //     {id:1111,ename:"Tanish",gender:"M"},
    //     {id:2222,ename:"Fahem",gender:"M"},
    //     {id:3333,ename:"Maaz",gender:"M"},
    //     {id:4444,ename:"jadav",gender:"M"}
    // ]}
    // db.employees.find(gender:'F'));
    
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

    // db.collection.insertMany([
    //     {
    //         name:"pl",
    //         value: 3.1415926`
    //     }
    // ]);

    // db.collection.find({value:{$type:'double'}});

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

    // db.students.insertMany([
    //     {
    //         Name: "Prem",
    //         Age: 19,
    //         Country_of_Origin: "India",
    //         Gender: "Male",
    //         Graduated: false,
    //         Postal_Address: [{Street:"C5 09 Kendriya Vihar Sector-11", City: "Navi Mumbai"}],
    //         Achievement: [
    //             { Award: "Startup Pitch", Year: 2024 },
    //             { Award: "Chess", Year: 2024 }
    //         ]
    //     }
    // ]);
    
    // _id: ObjectId('67359b84b9ac3359b542f807');

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

    // db.Employees.insertMany([
    //     { EmpId:045, FirstName:"John", LastName:"Doe", HireDate: new Date("01/01/2000") },
    //     { EmpId:150, FirstName:"Adam", LastName:"Doe", HireDate: new Date("01/01/2000")},
    //     { EmpId:09, FirstName:"Jessica", LastName:"Doe", HireDate: new Date("01/01/2000") },
    //     { EmpId:11, FirstName:"Elia", LastName:"Doe", HireDate: new Date("01/01/2000") },
    // ]);

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
    
    // db.usecase.insertMany([
    //     {Name: "Sam", Courses: "SQl Server, ASP.NET MVC, MongoDB"},
    //     {Name: "Mary", Courses: "Java, MongoDB"},
    //     {Name: "Tina", Courses: "MongoDB, PHP"},
    // ])

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

    // db.students.insertMany([
    //     { EId:11, Name:"John", gender:"M", dept: "Sales" },
    //     { EId:21, Name:"Joe", gender:"M", dept: "Marketing" },
    //     { EId:31, Name:"Ashwin", gender:"M", dept: "HR" },
    //     { EId:41, Name:"Katrina", gender:"F", dept: "IT" },
    //     { EId:51, Name:"Salman", gender:"M", dept: "Manager" },
    //     { EId:61, Name:"Ranbir", gender:"M", dept: "Stats" },
    //     { EId:71, Name:"Alia", gender:"F", dept: "IT" },
    //     { EId:81, Name:"Ashwin", gender:"M", dept: "HR" },
    // ]);
    // db.students.findOne({_id:11});

  xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
