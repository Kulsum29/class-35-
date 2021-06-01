Functions for database connection

database = firebase.database();

To create a reference

dataRef = database.ref('name of the data');

To read data continuously:

dataRef.on('value', function (data) { x = data.val();})

To overwrite data:

dataRef.set({ name: value })
