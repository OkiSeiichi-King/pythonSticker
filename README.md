### Getting Started

First, clone this repository:

```bash
git clone https://github.com/Solesca-Energy/junior_interview.git
```

### Frontend

Change directory to the frontend directory:

```bash
cd frontend
```

Then, start the development server:

```bash
yarn dev
```

If you don't have the Yarn package manager installed, make sure to install that first.

Open <a href='http://localhost:3000' target='_blank'>http://localhost:3000</a> with your browser to see the result.

### Backend

In a new terminal:\
Change directory to the backend directory:

```bash
cd backend
```

Create a new virtual environment (the "python3" keyword may change depending on how you have Python configured):

```bash
python3 -m venv venv
```

Then, activate the virtual environment:

```bash
source venv/bin/activate
```

or on Windows (cmd.exe):

```bash
venv\Scripts\activate.bat
```

There should now be a `(venv)` next to your name/hostname.\
\
Next, install the required Python packages:

```bash
pip install -r requirements.txt
```

Finally, start the Flask server:

```bash
flask run
```

**Whenever you make changes to your code, remember to restart the Flask server to apply those changes:**

```bash
CTRL+C
flask run
```
