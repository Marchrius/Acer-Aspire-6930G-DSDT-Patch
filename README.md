# Acer Aspire 6930G DSDT Patch

<!--- ![Icon](http://25.io/mou/Mou_128.png) -->

## Overview

This set of patches can be used in **DSDT Editor** or (preferably) **MaciASL** to apply
some common patches to your 6930G for running **OS X**.

### How To use this repo

#### Adding to MaciASL

* Run MaciASL
* choose Preferences from the MaciASL menu bar
* select Sources
* click the [+] button
* give it a name (eg. "Acer Aspire 6930G")
* type the following [http://raw.github.com/Marchrius/Acer-Aspire-6930G-DSDT-Patch/master](http://raw.github.com/Marchrius/Acer-Aspire-6930G-DSDT-Patch/master)

#### Using in MaciASL
* run MaciASL
* if you already have a patched DSDT in /Extra, MaciASL will load it (caption will say DSDT.AML)
* if you don't have a patched DSDT yet, caption will show *System DSDT*
* click Compile to verify you have an error free compile
  (only errors matter)
* if it has errors, you must fix them
* there are a few common error patches in the repo (first group)
* ok... back to how to apply a patch...
* click Patch (logical, right)
* select a patch from the repothat appears on the left
* MaciASL will show you a preview of the changes
* click Apply
* when you're done applying patches, click Close

