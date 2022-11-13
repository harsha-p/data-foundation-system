# Listing Platform (Part of the Data Foundation System)

## WHAT IT IS

* A basic versioning GUI for displaying the versions and changes in all  the datasets deployed on the site.
* The end product should be a dynamic website where all the functionalities should work smoothly

### FUNCTIONAL REQUIREMENTS

* Any user should be able to see the versions of all available datasets.
* A clean UI for previewing the dataset and the dataset metadata , describing
  * what it is
  * Date of release
  * Published by
  * Last updated
  * List of versions
* For  a person to make any changes he should be the published of that particular dataset and should be authenticated.
* Any user can view and download the available datasets with various available versions
* We have to keep track of all the versions of a dataset that are releaed on the website, from DAY-1
* For all the versions of a dataset, there should be meta data document that holds the following information:
  * Edit name (commit name)
  * Date of Publishing
  * Edit Message (commit message)
  * User-ID of the person who is creating the version

### DELIVERABLES

* Code base
* Deployed version of the Application

### TECH STACK

* Frontend: ReactJS
* Backend: Django
* Database: MySQL
* Object Storage: AWS S3
* Deployment: Docker
* Web Server: nginx
* CI/CD: GitLab CI/CD

```sh
cd backend
sudo chown -R $USER:$USER db
docker-compose build # build containers
docker-compose up -d # start containers -d for daemon
docker-compose down # stop containers
```
