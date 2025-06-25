# Dynamic Flashing Guide  

---

## Build Info

- **Dynamic GApps build**: Encrypted by default (FBEv2 + casefolding), based on **EROFS** system.
- **Dynamic Vanilla build**: Encrypted by default (FBEv2 + casefolding), based on **EXT4** system.

---

## 📦 Legacy to Dynamic Flashing (Encrypted)

1. Flash **Recommended OrangeFox dynamic recovery**
2. Flash **legacy2retrofit zip**
3. Flash **A11 firmware** (if coming from MIUI or older ROMs)
4. Flash **ROM**
5. **Format data**
6. **Reboot to system**  
   *(If possible, after the initial setup, go to Recovery and format the data again to avoid issues related to storage permissions.)*
7. ✅ Enjoy

---

## 🔄 Dirty Flashing from Previous Build

1. Flash **ROM**
2. Flash **GApps** *(if vanilla build)*
3. Wipe **dalvik + cache**
4. **Reboot**
5. ✅ Enjoy

---

## 🧼 Clean Flashing from Previous Build

1. Flash **ROM**
2. Flash **GApps** *(if vanilla build)*
4. Wipe **data + dalvik + cache**
5. **Reboot**
6. ✅ Enjoy

---

## Notes

- If your **data partition is on EXT4**, then after formatting data, **change it to F2FS**.

---
