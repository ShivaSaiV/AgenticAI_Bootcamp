## Set Up with UV Package Manager
- Much faster than pip
- https://docs.astral.sh/uv/
- Disadvantage: harder for working on multiple projects/environments

# Steps:
1. Install UV 
```bash 
pip install uv
```
2. Create folder and cd
```bash
uv init demouv
cd demouv
```
3. Create a virtual environment
```bash
uv venv
```
4. Activate venv
```bash
source .venv/bin/activate
```
5. Install packages
```bash
uv add pandas
```
