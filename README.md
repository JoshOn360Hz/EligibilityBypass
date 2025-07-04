# EligibilityBypass

This project documents the differences between eligibility-related system files on EU and non-EU iOS devices.

⚠️ **Disclaimer:**
- Modifying system files may violate Apple's Terms of Service and could be illegal in some jurisdictions.
- This project is intended for educational and research purposes only.

---

## Observed Files and Locations

- `/var/db/os_eligibility/eligibility.plist`
- `/private/var/MobileAsset/AssetsV2/com_apple_MobileAsset_OSEligibility/purpose_auto/[unique_id]/AssetData/config.plist`

These files influence device eligibility settings for regional features, such as alternate app marketplaces.

---

## Notes

- Differences between the `eligibility.plist` and `config.plist` files have been observed between EU and non-EU devices.
- On jailbroken devices, file management tools like **Filza** are commonly used to view and explore system files if the files are replaced with the files on this repo region restricted features wil be enabled.
- Alterations to these files on a jailbroken device may affect app marketplace availability.
- No instructions are provided on how to modify or replace these files. Users seeking to explore this further should refer to publicly available jailbreak and iOS development communities.

---

## Important

This repository is for **educational and informational purposes only**.  
You assume all risk and responsibility if you choose to modify your device outside of Apple's intended use.

