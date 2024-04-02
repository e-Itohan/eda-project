# Requiremnts and setup

## Requirements

- pyenv
- python==3.11.3

## Setup

* setting the python version locally to 3.11.3
* creating a virtual environment using the `venv` module
* activating your newly created environment 
* upgrading `pip` (This step is not absolutely necessary, but will save you trouble when installing some packages.)
* installing the required packages via `pip`


Please, check before that you met the requirements

```bash
pip freeze > requirements.txt
```

Installin the enviroment
```
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```
### **`WindowsOS`** type the following commands :

- Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    python.exe -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-bash` CLI :
    ```
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    python.exe -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

    **`Note:`**
    If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:
    ```Bash
    python.exe -m pip install --upgrade pip
    ```

In order to upgrade all packages in requirements.txt you can `pip install upgrade-requirements`
and then run: `upgrade-requirements`.
This will also automatically update the requirements.txt document.

# The clients

| Name                | client | Characteristics                                                                                                                                                                 |
| ------------------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Thomas Hansen       | Buyer       | 5 kids, no money, wants nice (social) neighborhood, Timing?, Location?                                                                                                          |
| Charles Christensen | Seller      | Invest with big returns, wondering about renovation?, which Neighborhood? Timing?                                                                                               |
| Bonnie Brown        | Seller      | Has house and wants to move soon (timing?), but wants high profit in middle class NH (neighborhood)                                                                             |
| Larry Sanders       | Buyer       | Waterfront , limited budget, nice & isolated but central neighborhood without kids (but got some of his own, just doesn't want his kids to play with other kids .. because of germs) |
| Nicole Johnson      | Buyer       | Lively, central neighborhood, middle price range, right timing (within a year)                                                                                                  |
| Jennifer Montgomery | Buyer       | High budget, wants to show off, timing within a month, waterfront, renovated, high grades, resell within 1 year                                                                                  |
| Bonnie Williams     | Seller      | Has several houses, some in bad neighborhoods, willing to evict people, timing?, big returns, open for renovations                                                              |
| William Rodriguez   | Buyer       | 2 people, country (best timing & non-renovated) & city house (fast & central location), wants two houses                                                                        |
| Erin Robinson       | Buyer       | Invest in poor neighborhood, buying & selling, costs back + little profit, socially responsible                                                                                 |
| Jacob Phillips      | Buyer       | Unlimited Budget, 4+ bathrooms or smaller house nearby, big lot (tennis court & pool), golf, historic, no waterfront                                                            |
| Zachary Brooks      | Seller      | Invests in historical houses, best neighborhoods, high profits, best timing within a year, should renovate?                                                                     |
| Timothy Stevens     | Seller      | Owns expensive houses in the center, needs to get rid, best timing within a year, open for renovation when profits rise                                                         |
| Amy Williams        | Seller      | Italian mafiosi, sells several central houses(top10%) over time, needs average outskirt houses over time to hide from the FBI                                                   |
  

# Column Names and descriptions for King County Data Set

- **id** - unique identified for a house
- **dateDate** - house was sold
- **pricePrice** - is prediction target
- **bedroomsNumber** - # of bedrooms
- **bathroomsNumber** - # of bathrooms
- **sqft_livingsquare** - footage of the home
- **sqft_lotsquare** - footage of the lot
- **floorsTotal** - floors (levels) in house
- **waterfront** - House which has a view to a waterfront
- **view** - Has been viewed
- **condition** - How good the condition is ( Overall ):  

| 1 | 2 | 3 | 4 | 5  
| ---|---|---|---|---  
| Poor | Fair | Avg | Good | Very Good   

- **grade** - overall grade given to the housing unit, based on King County grading system:  

| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12  
|---|---|---|---|---|---|---|---|---|---|---|---  
| Cabin | Substd. | Poor | Low | Fair | Low Avg. | Avg. | Good | Better | Very Good | Excellent | Luxury | Mansion   

- **sqft_above** - square footage of house apart from basement
- **sqft_basement** - square footage of the basement
- **yr_built** - Built Year
- **yr_renovated** - Year when house was renovated
- **zipcode** - zip
- **lat** - Latitude coordinate
- **long** - Longitude coordinate
- **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
- **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors  
