Q1
db.Sailors.find();

Q2
db.Product.find();

Q3
db.Sailors.find({}, { Sname: 1, _id: 0 });

Q4
db.Client.find({}, { City: 1, State: 1, _id: 0 });

Q5
db.Reserves.find({ Day: "10-oct-98" });

Q6
db.Sailors.find({ Rating: 7 }, { Sname: 1, Sid: 1, Age: 1, _id: 0 });

Q7
db.Product.find({ Cost_Price: 250 });

Q8
db.Client.find({ Baldue: 1000 }, { Cl_no: 1, Name: 1, City: 1, _id: 0 });

Q9
db.Product.updateMany({ Qty: 100 }, { $set: { Sell_Price: 675 } });

Q10
db.Client.updateMany({}, { $set: { State: "Gujarat" } });

Q11
db.Reserves.deleteMany({ Sid: 22 });

Q12
db.Product.deleteMany({ Reorder_Lvl: 50 });