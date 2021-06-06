# In simple terms what is a sub-document?
Its a document inside another document. Or a schema inside another schema
# When might you use a sub-document?
To add certain things related to one object or item as a sub category or class

# How do you add to a collection of sub-documents? What about editing them?
You can use the .findOne method to find the one you want to add to adn then the .ush method to add .
To edit them you just edit them like  regular array or object after finding it and saving it with .save