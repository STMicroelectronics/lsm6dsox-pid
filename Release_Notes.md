---
pagetitle: Release Notes for LSM6DSOX Component
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

<center>
# Release Notes for LSM6DSOX Component Driver
Copyright &copy; 2021 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# License

This software component is licensed by ST under BSD 3-Clause license, the "License".
You may not use this component except in compliance with the License. You may obtain a copy of the License at:

[BSD 3-Clause license](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the LSM6DSOX component drivers.
:::

::: {.col-sm-12 .col-lg-8}
# Update history

::: {.collapse}
<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 18-June-2021</label>
<div>

## Main changes

### First release

- First official release [ref. DS v3.0]

##

</div>

<input type="checkbox" id="collapse-section2" aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V2.0.0 / 19-April-2023</label>
<div>

## Main changes

- Fixed wrong implementation of lsm6dsox_interrupt_mode_get
- Add __weak directive to read/write registers routines
- Extend stmdev_ctx_t structure with mdelay callback

##

</div>

<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V2.0.1 / 01-June-2023</label>
<div>

## Main changes

- Fix Release_Notes.md

##

</div>

<input type="checkbox" id="collapse-section4" aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">V2.1.0 / 09-Nov-2023</label>
<div>

## Main changes

- moved all enum outside of struct to be C++ compliant
- Fix "maybe uninitialized variable" warnings

##

</div>

<input type="checkbox" id="collapse-section5" aria-hidden="true">
<label for="collapse-section5" aria-hidden="true">V3.0.0 / 20-Mar-2024</label>
<div>

## Main changes

- Fixed code style (Artistic Style Version 3.4.13)
- Add "const" to ctx arg for all APIs
- Fix driver build with optimization level O2

##

</div>

<input type="checkbox" id="collapse-section6" aria-hidden="true">
<label for="collapse-section6" aria-hidden="true">V3.0.1 / 20-Jun-2024</label>
<div>

## Main changes

- updated README.md file with tag reference and mdelay description

##

</div>

<input type="checkbox" id="collapse-section7" aria-hidden="true">
<label for="collapse-section7" aria-hidden="true">V3.1.0 / 18-Dec-2024</label>
<div>

## Main changes

- Read always both FIFO_STATUS1 and FIFO_STATUS2 regs

##

</div>

<input type="checkbox" id="collapse-section8" aria-hidden="true">
<label for="collapse-section8" aria-hidden="true">V3.2.0 / 07-Jul-2025</label>
<div>

## Main changes

- Fix driver formatting options
- Added pointer to private data in stmdev_ctx_t

##

</div>

<input type="checkbox" id="collapse-section9" checked aria-hidden="true">
<label for="collapse-section9" aria-hidden="true">V3.3.0 / 07-Oct-2025</label>
<div>

## Main changes

- Added checks before writes and membank setting
- Removed useless membank switch in int_notification_get API
- Refactor ln_pg_write_byte to use ln_pg_write
- Adding CODE_OF_CONDUCT.md and SECURITY.md

##

</div>
:::

:::
:::

<footer class="sticky">
::: {.columns}
::: {.column width="95%"}
For complete documentation on LSM6DSOX,
visit:
[LSM6DSOX](https://www.st.com/content/st_com/en/products/mems-and-sensors/inemo-inertial-modules/lsm6dsox.html)
:::
::: {.column width="5%"}
<abbr title="Based on template cx566953 version 2.0">Info</abbr>
:::
:::
</footer>
