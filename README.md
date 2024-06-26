# Alu-AirBnB_clone
Welcome to the AirBnB clone project! This project aims to build a simplified version of the AirBnB platform, focusing on the management of objects related to accommodations.
# We will need to:

- put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances

- create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file

- create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel

- create the first abstracted storage engine of the project: File storage.

- create all unittests to validate all our classes and storage engine

# Our command interpreter would be able to:

- Create a new object (ex: a new User or a new Place)

- Retrieve an object from a file, a database etc…

- Do operations on objects (count, compute stats, etc…)

- Update attributes of an object

- Destroy an object
