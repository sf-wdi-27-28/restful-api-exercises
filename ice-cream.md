Now its your turn.

Say we want to create an API similar to the one above, that returns data about icecream. We need to be able to get information about specific flavors, as well as all of the flavors we have in our database. We also want to get some flavors by category, like "fruity", "gluten free", or "chunky". Finally we want to add one POST route that allows users of our API to add new flavors!

GET ICECREAM "/icecream/id:froyo"

GET ICECREAM: "/icecream/:id:extrafat"

GET ICECREAM "/icecream/:id:skinny"

app.post('/api/icecream', function(req,res) {
  res.json(icecream);
});
