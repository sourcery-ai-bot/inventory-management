# bc-X-inventory
## Inventory Management
This app should be able to keep inventory of Andela’s assets, mainly electronics e.g. **laptop, projector, cables, etc.**
The admins for this app, are staff members in the Ops and Facilities Department and the rest are staff members (and fellows).

1. As a super-admin, I should be to sign-in and add other admins
2. As an admin, I should be able to sign-in
3. As an admin, I should be able to add an asset record, with the following details:

  * Asset Name
  * Description
  * Serial Number
  * Andela Serial Code
  * Date bought
  * Etc.
4. As an admin, I should be able to assign an asset to a staff member. I should add the date for reclaiming back the asset
5. As an admin, I should be able to un-assign (reclaim) an asset from a staff member
6. As an admin, I should be able to see a list of assigned assets (and their assignees) and a list of available (unassigned) items 
7. As an admin, I should be able to see a reminder (notification) for items that are to be reclaimed soon, or the reclaiming date has passed
8. As a user (staff member), I should be able to report a case of an item getting lost
9. As a user (staff member), I should be able to report a case of a lost-and-found item
10. As an admin, I should be able to view all the cases of lost items, and lost-and-found items Idea
11. As an admin, I should be able to mark a case as resolved (appropriately), with some description

### Installation
Clone this repo in a virtual environment in your machine the install required dependencis using the **requirements.txt** file. You install the required dependencies using pip by running the following command on your terminal once your have activated your virtual environment:

  > pip install -r requirements.txt

### Dependencies
The application is making use of the following Flask dependencies.

1. Flask==0.10.1
2. Flask-SQLAlchemy==1.0
3. Flask-WTF==0.10.0
4. Jinja2==2.7.3
5. Flask-Login==0.3.2
6. Flask-Bootstrap==3.1.1.2 
7. MarkupSafe==0.23
8. SQLAlchemy==0.9.7
9. WTForms==2.0.1
10. Werkzeug==0.9.6
11. coverage==3.7.1
12. gunicorn==19.0.0
13. itsdangerous==0.24
