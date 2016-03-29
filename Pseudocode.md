
## ICE CREAM GET/POST PSEDUDOCODE

- GET ALL ICE CREAM ``"/ice_cream"``
- GET ICE CREAM BY FLAVOR ``"/ice_cream/:flavors"``
- GET ALL FRUITY FLAVORS ``"/ice_cream/:flavors/fruity"``
- GET ALL GLUTEN FREE FLAVORS ``"/ice_cream/:flavors/gluten_free"``
- GET ALL CHUNKY FLAVORS ``"/ice_cream/:flavors/chunky"``
- POST NEW FLAVORS
````"api.post('api/ice_cream/:flavors", function flavorsCreate(req, res){
var name = req.body.name;
var desc = req/body.description;
var newFlavor = {name: name, description:desc};
flavors.push(newFlavor);
res.json(flavors);
});````
