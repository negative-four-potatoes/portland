# Interrupt vector table documentation
## Notes
You may want to read <https://en.wikipedia.org/wiki/Interrupt_vector_table> before reading this page.  If you are looking for a listing of the interrupts available to developers of applications for portland, see <https://negative-four-potatoes.github.io/portland/developers/interrupts>.

## Listing
* Constants
  * [`IVT_START`](#ivt_start)
* Functions
  * [`ivt_set_up`](#ivt_set_up)

---
## `IVT_START`
Value: `0x0000`

This defines the start of the IVT, as defined in [the layout](layout).

## `ivt_set_up`
Signature: `void (void)`

This sets up the IVT.  The kernel calls it at startup.

---
**[Back to index](index)**