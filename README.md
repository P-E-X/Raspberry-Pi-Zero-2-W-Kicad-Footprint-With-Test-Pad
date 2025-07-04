# Raspberry-Pi-Zero-2-W-Kicad-Footprint-With-Test-Pad
A non official footprint for raspberry pi zero 2 w with test pad. work with 90025-AS

## Compatible Spring-Loaded pin:
https://www.mouser.com/ProductDetail/Preci-dip/90025-AS?qs=RNeFVNNVJyHHutbD2vLaqg%3D%3D
 SMD/SMT Mounted

## KiCad Footprint Import Guide (.kicad_mod)

This guide provides instructions for importing individual KiCad footprints saved as `.kicad_mod` files into your KiCad libraries.

**Note:** These instructions are for KiCad version 6 and later. If you are using an older version, the process may differ slightly.

**Method 1: Adding a Library (Folder) Containing the Footprint**

This method is suitable when you have one or more `.kicad_mod` files within a folder, and you want to add that entire folder as a new library.

**1. Locate the .kicad_mod file(s):**

*   Identify the folder containing the `.kicad_mod` file(s) you wish to import.
*   If the files are in a compressed archive (e.g., .zip), extract the contents to a folder.

**2. Open the KiCad Footprint Editor:**

*   Launch KiCad and access the Footprint Editor, which is typically found under the "Tools" menu in the project manager.

**3. Manage Footprint Libraries:**

*   Within the Footprint Editor, navigate to `Preferences > Manage Footprint Libraries`.

**4. Add the Folder as a New Library:**

*   In the "Footprint Library Tables" dialog, choose the appropriate tab (e.g., `Global Libraries` for availability in all projects).
*   Click the `Browse Libraries` button (often a folder icon).
*   Browse to and select the folder containing your `.kicad_mod` files (you select the *folder*, not the individual file).
*   Click `Select Folder` or `Open`.

**5. Confirm the Library:**

*   The selected folder will be listed as a new library entry.
*   Click `OK` to close the dialog.

**6. Verify the Footprint:**

*   In the Footprint Editor's "Libraries" panel, search for the imported footprint.
*   Double-click to open it for review.

**Method 2: Importing a Single Footprint to an Existing Library**

This method is useful when you have a single `.kicad_mod` file and want to add it to an existing library.

**1. Open the Footprint Editor:**

*   Launch KiCad and open the Footprint Editor.

**2. Import the .kicad_mod file:**

*   Go to `File > Load Footprint > Import footprint from KiCad file...`.
*   Browse to the `.kicad_mod` file, select it, and click `Open`.

**3. Load the Footprint:**

*   The footprint will be loaded onto the editor's canvas.

**4. Set the Active Library:**

*   To save the footprint to an existing library, set that library as the active one by going to `File > Set Active Library` and selecting the desired library from the list.

**5. Save to the Active Library:**

*   With the correct library active, go to `File > Save Footprint in Active Library`.
*   Click `OK` or `Save`.

**6. Verify the Import:**

*   Check the active library in the Footprint Editor to ensure the newly imported footprint is listed.

**Important Considerations:**

*   **System Libraries:** Avoid saving custom footprints to system libraries, as updates may overwrite them.
*   **Creating a Custom Library:**  If needed, create a dedicated library for your custom footprints for better organization and management.
*   **.pretty Folders:** KiCad footprint libraries (v6+) are typically folders with a `.pretty` extension.
*   **Renaming:** You can rename imported libraries in the "Footprint Library Tables" dialog if needed.

This revised guide provides more explicit steps for both methods, emphasizes important considerations, and clarifies points based on your feedback.  It should be ready for use on GitHub.
