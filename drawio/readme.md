
# Add Custom Libraries to DrawIO

[Load a custom library from the web](https://www.drawio.com/blog/public-custom-libraries)

You can load the libraries directly from Github by using the 'RAW' url.

# RAW URLs

```
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Battery.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Battery-Lithium.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Bms.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Busbar.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Charger.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Circuit-Breaker.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Combiner.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Communication.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Connector.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Controller.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Converter.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Display.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Distribution.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Fuse.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Generator.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Icon.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Inverter-Charger.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Inverter.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Isolation-Transformer.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Isolator.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Miscellaneous.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Mppt.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Sensor.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Shunt.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Solar-Charge-Controller.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Solar.xml
https://raw.githubusercontent.com/gbonk/shape-library/refs/heads/main/drawio/Switch.xml

```

# Add directly to DrawIO configuration

The raw URLs are required to be encoded and prepended with a 'U'

Click the 'Extras' menu, select 'Configuration' then the Preferences button.

[Sample DrawIO Preferences](drawio.md)

NOTE: May take a moment or two to load as some libraries are rather large.

### DrawIO

```
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FBattery.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FBattery-Lithium.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FBms.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FBusbar.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FCharger.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FCircuit-Breaker.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FCombiner.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FCommunication.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FConnector.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FController.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FConverter.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FDisplay.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FDistribution.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FFuse.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FGenerator.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FIcon.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FInverter-Charger.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FInverter.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FIsolation-Transformer.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FIsolator.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FMiscellaneous.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FMppt.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FSensor.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FShunt.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FSolar-Charge-Controller.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FSolar.xml",
"Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fgbonk%2Fshape-library%2Frefs%2Fheads%2Fmain%2Fdrawio%2FSwitch.xml"
```
