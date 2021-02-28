
# Setup
* PYHTON VERSION MUST BE 3.6.9

* Choose the folder coresponding to your Operating system : 

        cd <OPERATING_SYSTEM>

* Install virtual environment using pip:

        python3 -m pip install --user virtualenv

* Create a virtual environment at your work directory <WORKDIR>  (UNIX):

        virtualenv <WORKDIR>/real_estate_scrape
        source <WORKDIR>/real_estate_scrape/bin/activate

* Install packages with:

        pip install -r requirements.txt

# Run

* Choose the folder coresponding to your Operating system : 

        cd <OPERATING_SYSTEM>

* Activate a virtual environment<WORKDIR>  (UNIX):

        source <WORKDIR>/real_estate_scrape/bin/activate
        
- (HISTORY) To scrape all houses:

        python main.py --command all

- (MONTHLY) to scrape the last 30 days:

        python main.py --command 30days

- (FAST TEST) To scrape n houses of each category:

        python main.py --command test n


