**Activate the virtual environment**
```
source blockchain-env/bin/activate
```
**Run the application and API**

```
python3 -m backend.app
```
**Run a peer instance**

```
export PEER=True && python3 -m backend.app
```
**Run the frontend**
```
npm run start
```
**Seed the backend with data**

Make sure to activate the virtual environment.

```
export SEED_DATA=True && python3 -m backend.app
```