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
<input type="checkbox" id="collapse-section11" checked aria-hidden="true">
<label for="collapse-section11" aria-hidden="true">V3.4.0 / 08-Oct-2026</label>
<div>

## Main changes

- Fix temperature_raw_get() API
- Fix xl/gy data_rate_Set API
- Fix build warnings
- Fix MISRA issues
- Refactor: applied style fix, add const to pointers
- Refactor all_sources_get API
- Refactor pin_int1_route_set/get and pin_int2_route_set/get
- Add shift in sh_slv_cfg_write API to use 7bit representation
- Fix fifo_watermak_set and pedo_steps_period_get
- Added missing write in ff_dur_set API
- Add read in mem_bank_set API
- Fix MISRA issue: Add initialization to all variables
- Fix MISRA issue: Replace enum entry with hex value
- Change lsm6dsox_data_t enum names
- Change mag_soft_iron_set/get number type, unsigned to signed
- Fix fsm_out_t struct
- Remove the reg_t union struct
- Add parameter names to stmdev read/write/delay functions
- Define __weak macro for weak function declarations
- Fix sleep_change_ia bits size for wake_up_src struct
- Add unsigned specification to register address definition
- Fix fsm_int1_b_t struct definition
- Add int1_mode_set/get API
- Remove not implemented API from header
- Replace sh_slv_cfg_x_read with generic sh_slv_cfg_read using index
- Change sh_read_data_raw_get API, remove emb_sh_read_t struct
- Improved some APIs to use ln_pg_read/write on more bytes
- Align ln_pg_write/read to other drivers implementation
- Replace sh_batch_slave_x with generic sh_batch_slave that use idx
- Fix typo: STEP_CPUNTER_TAG replace with STEP_COUNTER_TAG
- Fix aux_den_polarity_get, wrong reg is used
- Minor documentation improvement
- Add checks before writes and membank setting
- Fix pin_conf_get API
- Add const pointer in write_reg API

##

</div>

<input type="checkbox" id="collapse-section10" aria-hidden="true">
<label for="collapse-section10" aria-hidden="true">V3.3.1 / 18-Mar-2026</label>
<div>

## Main changes

- Re-order update history (most updated on top)

##

</div>
<input type="checkbox" id="collapse-section9" aria-hidden="true">
<label for="collapse-section9" aria-hidden="true">V3.3.0 / 07-Oct-2025</label>
<div>

## Main changes

- Added checks before writes and membank setting
- Removed useless membank switch in int_notification_get API
- Refactor ln_pg_write_byte to use ln_pg_write
- Adding CODE_OF_CONDUCT.md and SECURITY.md

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

<input type="checkbox" id="collapse-section7" aria-hidden="true">
<label for="collapse-section7" aria-hidden="true">V3.1.0 / 18-Dec-2024</label>
<div>

## Main changes

- Read always both FIFO_STATUS1 and FIFO_STATUS2 regs

##

</div>

<input type="checkbox" id="collapse-section6" aria-hidden="true">
<label for="collapse-section6" aria-hidden="true">V3.0.1 / 20-Jun-2024</label>
<div>

## Main changes

- updated README.md file with tag reference and mdelay description

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

<input type="checkbox" id="collapse-section4" aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">V2.1.0 / 09-Nov-2023</label>
<div>

## Main changes

- moved all enum outside of struct to be C++ compliant
- Fix "maybe uninitialized variable" warnings

##

</div>

<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V2.0.1 / 01-June-2023</label>
<div>

## Main changes

- Fix Release_Notes.md

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

<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 18-June-2021</label>
<div>

## Main changes

### First release

- First official release [ref. DS v3.0]

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
