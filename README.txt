Python basic packages(for linux offline install, python 3.7.11)

# Install command
pip install --no-index --find-links=. *.whl

(download command: pip download --python-version 3.7.11 --platform manylinux1_x86_64 --only-binary=:all: --no-binary=:none: -r requirements.txt)