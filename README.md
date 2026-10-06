# IFS of ETH Oberon, for polpo

Barnsley's iterated function systems: fractals (a fern, a dragon, coral, crystals, trees ...)
drawn from a handful of numbers, in an XYplane viewer of the desktop.

    IFS.Tool    the tool text with twelve examples (by W. Ibl)
    IFS.Mod     IFS.Init x0 y0 e <the 28 coefficients> ~   and   IFS.Draw (press "s" to stop)

From ETH Oberon (OLR), the module converted to plain text, the tool text as it is (an Oberon
text). It needs the packages xyplane and randomnumbers (and so math).

Install with portia: `portia.Install ifs`; then open `IFS.Tool` in the desktop and click
`IFS.Init` and `IFS.Draw` under an example. The license is GPL-3 (`LICENSE`); the code comes from ETH Oberon, whose license (`LICENSE.ETH`)
asks to keep its copyright notice and conditions, which `LICENSE.ETH` does.
