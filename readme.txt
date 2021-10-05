pip: python -m pip install pip --upgrade
pygame: python -m pip install -U pygame --user
auto-py-to-exe:
cd %userprofile%/desktop
git clone https://github.com/brentvollebregt/auto-py-to-exe.git
python setup.py install
auto-py-to-exe
;
cd %userprofile%/desktop
pip install auto-py-to-exe
python setup.py install
auto-py-to-exe
