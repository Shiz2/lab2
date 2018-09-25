# Lab 2

In the server.js, we use the function:
app.get('/gallery/:gallery_id', async (req, res)
to handle the request for the gallery objects. In the function, the objects in a gallery are fetched by filtering the objects by the gallery_id.
The data returned from the fetching gallery objects is then preprocessed by iterating through every object and:
-> if there is no image url provided, set the object.image to be "No image"
-> if the image url is project, create an image tag
-> create a string to store the people affiliated to the object
The object with the ubdated information are then stored in array of objects which is then passed into the gallery template that is rendered.



