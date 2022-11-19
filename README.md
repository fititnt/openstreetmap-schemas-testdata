# openstreetmap-schemas-testdata
[draft] See https://community.openstreetmap.org/t/openstreetmap-dtd-xsd-json-schema-etc-for-commonly-shared-data/5653

## temp notes

```bash
xmllint --noout --schema temp-schema/osm-wiki-api-capabilities-v06.xsd tests/data/C00002.xml

# https://lists.openstreetmap.org/pipermail/dev/2012-March/024659.html
curl http://www.openstreetmap.org/api/0.6/relation/65559 --output temp/rel-test.xml
xmllint --noout --schema osm0.6.xsd temp/rel-test.xml
```


## Disclaimers
<!--
TODO see https://wiki.osmfoundation.org/wiki/Trademark_Policy
-->

OpenStreetMap™ is a trademark of the OpenStreetMap Foundation, and is used with their permission.
This project is not endorsed by or affiliated with the OpenStreetMap Foundation.
