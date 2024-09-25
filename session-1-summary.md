# Create python enviroment

**1) Open a Terminal or Command Prompt.**

2) Navigate to Your Project Directory:

```bash
cd path/to/your/project
```
3) Create the Virtual Environment: Run the following command, replacing myenv with your desired environment name:

```bash
python -m venv myenv
```
4) Activate the Virtual Environment:

On Windows:
```bash
myenv\Scripts\activate
```

5) Install Packages: After activating the environment, you can install packages using pip:

```bash
pip install package_name
```
6) Deactivate the Virtual Environment: When you're done working, you can deactivate the environment with:

```bash
deactivate
```
7) Optional: Requirements File
If you want to create a requirements.txt file to track your dependencies, run:

```bash
pip freeze > requirements.txt
```
8) You can later install the same dependencies in another environment with:

```bash
pip install -r requirements.txt
```

Summary
1) Create the environment: python -m venv myenv
2) Activate it: source myenv/bin/activate (or myenv\Scripts\activate on Windows)
3) Install packages as needed.
4) Deactivate when finished.