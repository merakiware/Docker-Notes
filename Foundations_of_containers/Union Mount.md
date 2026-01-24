A union mount combines multiple filesystem layers into a single view, where changes are 
written to the top layer while lower layers remain unchanged.
This is how Docker containers stay lightweight the  base images are read-only, your changes live on top
