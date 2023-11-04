# python-web-pyramid-api-dolt-pop

## Description
Simple web app for a pyramid project that
serves an api. Query and lists all in `pop`
table.

## Tech stack
- python
    - sqlalchemy
    - pyramid
- dolt

## Docker stack
- python
- dolthub/dolt-sql-serverdb

## To run
`sudo ./install.sh -u`
- Endpoints
    - [Html](http://localhost)
    - [Api](http://localhost/pop)

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Pyramid setup](https://docs.pylonsproject.org/projects/pyramid/en/latest/index.html)
- [Sqlalchemy setup](https://docs.pylonsproject.org/projects/pyramid-cookbook/en/latest/database/sqlalchemy.html)
- [Json setup](https://docs.pylonsproject.org/projects/pyramid/en/latest/narr/renderers.html)
