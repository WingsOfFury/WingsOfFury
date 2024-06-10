// Model & generate Live JSON data values
// interactively using a simple syntax.
// String is the default value type
product = Live JSON generator

// Number, Date & Boolean are also supported
// Specify types after property names
version n = 3.1
releaseDate d = 2014-06-25
demo b = true

// Tabs or spaces define complex values
person
  id number = 12345
  name = John Doe
  phones
    home = 800-123-4567
    mobile = 877-123-1234

  // Use [] to define simple type arrays
  email[] s = jd@example.com, jd@example.org
  dateOfBirth d = 1980-01-02
  registered b = true

  // Use [] or [n] to define object arrays
  emergencyContacts[]
    name s = Jane Doe
    phone s = 888-555-1212
    relationship = spouse
  emergencyContacts[]
    name s = Justin Doe
    phone s = 877-123-1212
    relationship = parent

// See our Help page for additional info
// We hope you enjoy the tool!
