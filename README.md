# CRUD
Hospital server assignment


ADDING THE FILES  (POST):
Enter the URL: http://localhost:3000/hospitals.
Switch to the "Body" tab.
Choose "raw" and select JSON (application/json).
Enter the hospital data in the body. For example:
json
Copy code
{
  "name": "New Hospital",
  "patientCount": 100,
  "location": "City"
}
Click "Send."




GET Operation(RETRIEVE):

Open Postman.
Set the request type to GET.
Enter the URL for getting all hospitals: http://localhost:3000/hospitals.
Click "Send."
GET Operation for a Specific Hospital:

Set the request type to GET.
Enter the URL for a specific hospital (replace hospital_name with the actual hospital name): http://localhost:3000/hospitals/hospital_name.
Click "Send."



PUT Operation(UPDATE):

Set the request type to PUT.
Enter the URL for updating a specific hospital (replace hospital_name with the actual hospital name): http://localhost:3000/hospitals/hospital_name.
Switch to the "Body" tab.
Choose "raw" and select JSON (application/json).
Enter the updated hospital data in the body. For example:
json
Copy code
{
  "name": "Updated Hospital",
  "patientCount": 150,
  "location": "New City"
}
Click "Send."



DELETE Operation:

Set the request type to DELETE.
Enter the URL for deleting a specific hospital (replace hospital_name with the actual hospital name): http://localhost:3000/hospitals/hospital_name.
Click "Send."
These steps simulate the CRUD operations on the hospital data using Postman. Adjust the URLs and data according to your needs.
