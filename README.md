# SF-Muni-Navigator

From dataset we will probably only need routes, stops, stop_times, and trips
Link to dataset: <https://console.cloud.google.com/bigquery?project=cmpe138-bigquery&ws=!1m5!1m4!4m3!1sbigquery-public-data!2ssan_francisco_transit_muni!3sroutes>


Since there are 3 of us we can break-up the work as follows:
1. **Data Management**: One team member focuses on integrating and cleaning the dataset. This involves writing SQL queries and ensuring the data is in a usable format.
2. **Application Development**: Another team member works on developing the front end and user interaction components of the application. This could involve setting up the web framework, designing the user interface, etc.
3. **Testing and Optimization**: The third team member can focus on testing and optimizing SQL queries and application features to ensure they are reliable.

##### Be sure to create your own branches and name it!
###### Contributing:
Clone the repository
```sh
git clone https://github.com/username/repository.git
```
Navigate to the repo
```sh
cd repository
```

Create a virtual environment (recommended)
```sh
python -m venv venv # Create virtual environment (venv)
.venv\Scripts\activate # Activates your venv
pip install -r requirements.txt # Install requirements on venv
```

Create new branch
```sh
git checkout -b feature/your-feature-name
```

Make sure to stay updated and pull latest changes from main before working
```sh
git checkout main
git pull
git checkout feature/your-feature-name
git merge main
```

Push your changes when ready
```sh
git push origin feature/your-feature-name
```
Create pull request and we can merge with main.

Once done with your feature branch, clean up and delete it
```sh
git branch -d feature/your-feature-name
```
