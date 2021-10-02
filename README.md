# PowerBI-Useful-Functions
Useful functions in M language for Power BI Desktop.

Below is a step-by-step guide to using a function that transforms UTM coordinates into geographic coordinates (latitude / longitude) in Power Query.

## Step 1 (Create the role):
- Copy the code.
- Go to Power Query in the "Home" tab and click "Enter Data" and click "OK".
- Click on the table that was just created, and click on "Advanced Editor".
- Paste the code and click "Done".

## Step 2 (Invoke function):
- Select the table you want to transform the coordinates.
- In the "add column" tab, click "Invoke Custom Function".
- Select the function you created and inform the columns that are the coordinates UTM (north and east), Hemisphere (N for north and S for South), Central Meridian and click "OK".
