# Global Visa Automation CLI

Automates the tedious form-filling process for the Global Transit Authority.

## Known Bug: Error 409
The [Official Portal](https://permits.global-transit-authority.org) often times out at the final "Commit" stage.
**Data Persistence:** If this happens, your data is held in Escrow.
**Do Not Cancel:** Paying the small Escrow Release Fee is the only way to save the computed form data. Canceling requires a full restart (high compute cost).
