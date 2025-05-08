# DIY Stencil Printer

A compact, 3D-printed stencil printer for applying solder paste to single- and double-sided PCBs.
The printer attaches securely to any metal surface using magnets for added stability during use.

For optimal results, your stencil should have a 10 mm border around the PCB. Larger borders require offsetting the PCB from the frame’s edge, which may hinder repeatable application without manual realignment.

To operate, insert the PCB and stencil, align the stencil precisely, and clamp it in place using screws and wing nuts.

The design is fully parameterized in FreeCAD, allowing easy customization for different PCB sizes and thicknesses.

The .stl files in this repository are generated with the [default parameters](#model-parameters).

## Additional Hardware

 - 5 magnets (Ø15 mm × 2 mm), e.g.: [Amazon link](https://www.amazon.de/-/en/dp/B0C6279R9M)
 - 3 M6 screws (length > 20 mm)
 - 3 M6 wing nuts

## Model parameters

| Name            | Description                 | Default |
|-----------------|-----------------------------|---------|
| PCB Height      | Thickness of PCB            | 1.6mm   |
| PCB Length      | Maximum length of PCB       | 120mm   |
| PCB Width       | Maximum width of PCB        | 120mm   |
| Magnet Diameter | Diameter of mounting magnet | 15mm    |
| Magnet Height   | Height of mounting magnet   | 2mm     |

## LICENSE

The DIY Stencil Printer is marked with CC0 1.0 