# aptfilesearch

aptfilesearch provides a web interface for searching through debian/ubuntu files in all packages

<table>
  <tr>
    <td>
<img src="https://i.imgur.com/pqgTuj4.png">
    </td>
    <td>
<img src="https://i.imgur.com/TRgvOZO.png">
    </td>
  </tr>
  </table>

## API Prerequesites

```
apt install python3-venv apt-file
sudo apt-file update
```

## API Installation

```
git clone https://github.com/dvolk/aptfilesearch2/api
cd aptfilesearch2/api
python3 -m venv env
./env/bin/pip install fastapi uvicorn jinja2
```

## API Running

```
./env/bin/uvicorn main:app --reload
```

## APP installation

set up a virtual host and move `app/index.html` to the virtual host root directory
