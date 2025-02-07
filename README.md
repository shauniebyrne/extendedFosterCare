# Extended Foster Care
Extended Foster Care website for coaches and housing providers
---
---

# Login Page
User will either sign in using username, password, and ranking (admin, coach, or provider) on file or click "create account" to create a new account. When clicked on "create account" the user is redirected to the account page. Password should be encrypted as it enters database. The admin should gain access to every page in the website. The Coach should be directed to the map page once signed in and should only have access to the map, building, and unit pages. The housing provider should be directed to the provider page once signed in and only have access to provider page and form pages.
---

# Account Page
User will enter their wanted username, email, password, confirm password (background needs to make sure both passwords match), and ranking (admin, coach, or provider). Password should be encrypted as it enters database. When user clicks "create account" data should go to database and be stored in a login table to be referenced for the login page. Redirect user to login page once account data is sent to database (when "create account" button is pressed).
---

# Form Page (provider)
---
# Building Form
The Provider will fill out this form for all the buildings they own that they want available to be rented out. The form's info will be directed to the database to be able to be retrieved later on the provider, map, building info, unit info, buildings, and units pages.

# Unit Form
The Provider will fill out this form for all the units they own that they want available to be rented out. The form's info will be directed to the database to be able to be retrieved later on the provider, map, building info, unit info, buildings, and units pages.
---

# Provider Page (provider)
The Provider is directed to this page after logging in. Here, they will be able to see a list of all their buildings and associated units. They should be able to edit the information here (via a button with a link to a new form) or be able to delete all the information for that specific unit or building.
---

# Map Page (coach)
The coach should be directed to this page automatically after logging in. This page will have a map with pins to all the available buildings. The top will also have a filter where the coach can click on things they want included in buildings, and the filter will only show buildings that are available with those specific items. The coach can then click on the pin and be taken to the buildingInfo.html page via a link.
---

# Building Info Page (coach)
This page (as shown) has the provider info at the top and then the building info underneath. The coach can then click on the name of the building and be directed to the unitInfo.html page.

# Unit Info Page (coach)
This page (as shown) has the provider info at the top, the building info next, and then all the available units with their info. A coach can then click on the "rent" button and rent out the unit for their client. Once the unit is rented, it should not show up as available until it is no longer rented.
---

# Buildings Page (coach)
This page can be accessed by a coach via the navigation bar at the top of the page and will list all available buildings. The Provider's name will be attached (accessed through database) and number of available units for that building. Link will be attached to name of building so they can be directed to unitInfo.html page so they can press the "rent" button.
---

# Units Page (coach)
This page can be accessed by a coach via the navigation bar at the top of the page and will list all available units. The Providers name and building name will be added (accessed through database) and the name of the unit will be linked to unitInfo.html so they can press the "rent" button.
---