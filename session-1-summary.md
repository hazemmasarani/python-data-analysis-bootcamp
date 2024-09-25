# Create python enviroment

1) Open a Terminal or Command Prompt.

2) Navigate to Your Project Directory:

```bash
cd path/to/your/project
```
Create the Virtual Environment: Run the following command, replacing myenv with your desired environment name:

```bash
python -m venv myenv
```
Activate the Virtual Environment:

On Windows:
```bash
myenv\Scripts\activate
```

Install Packages: After activating the environment, you can install packages using pip:

```bash
pip install package_name
```
Deactivate the Virtual Environment: When you're done working, you can deactivate the environment with:

```bash
deactivate
```
Optional: Requirements File
If you want to create a requirements.txt file to track your dependencies, run:

```bash
pip freeze > requirements.txt
```
You can later install the same dependencies in another environment with:

```bash
pip install -r requirements.txt
```

Summary
Create the environment: python -m venv myenv
Activate it: source myenv/bin/activate (or myenv\Scripts\activate on Windows)
Install packages as needed.
Deactivate when finished.