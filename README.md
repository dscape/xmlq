# xmlq

The next best thing after JSONx

Filter XML with xpath.

``` sh
echo "<a>foo <b><c>hey</c></b></a>" | \
  xmlq /a | \
  DEBUG=* xmlq //b
```

