# Experiment - 2
# Recover deleted or damaged files from a storage device using Test Disk
 

## Aim  
To recover deleted or damaged files from a storage device using **TestDisk**, a forensic recovery tool.  

---

## Description  
In digital forensics, recovering deleted or corrupted files is an essential step during investigations. When files are deleted, their entries are removed from the file system, but the actual data often remains on the storage media until overwritten. TestDisk is an open-source forensic tool designed to recover lost partitions, fix disk errors, and restore deleted files.  

In this experiment, we use TestDisk to identify and restore deleted or damaged files from a storage device, ensuring data integrity for forensic analysis.  

---


## Tools & Equipment Used
- Test disk (Software)

- Source Drive: A USB flash drive or hard disk containing data.

- Destination Drive: Internal hard drive is enough with sufficient free space to store the recovered data


### Link to download Testdisk
[Click to download](https://www.cgsecurity.org/Download_and_donate.php/testdisk-7.3-WIP.win64.zip)

---

## Procedure  

**Launch TestDisk**  
   - Open the TestDisk tool (from command line or executable).  
   ![alt text](https://github.com/saravanakannana/digital-forensics-experiments-2025/blob/3fff276d0c1a43868a5a716633836cdd247416c2/img/df%20exp%202%20(1).png)

   - Run it with administrative privileges for full access.


**Select Create/Append Log**  
   - On startup, choose **Create** to generate a log file for documentation.  
    ![alt text](https://github.com/saravanakannana/digital-forensics-experiments-2025/blob/3fff276d0c1a43868a5a716633836cdd247416c2/img/df%20exp%202%20(2).png)


**Choose the Storage Device**  
   - TestDisk lists all available storage devices.
    ![alt text](https://github.com/saravanakannana/digital-forensics-experiments-2025/blob/3fff276d0c1a43868a5a716633836cdd247416c2/img/df%20exp%202%20(3).png)

   - Use the arrow keys to select the target device.  


**Select Partition Table Type**  
   - TestDisk detects the partition table type (e.g., Intel/MBR, EFI GPT).
    ![alt text](https://github.com/saravanakannana/digital-forensics-experiments-2025/blob/3fff276d0c1a43868a5a716633836cdd247416c2/img/df%20exp%202%20(4).png)

   - Confirm the suggestion by pressing **Enter**. 


**Analyze the Disk**  
   - Select **Analyse** → Quick Search to find lost partitions.  
   ![alt text](https://github.com/saravanakannana/digital-forensics-experiments-2025/blob/3fff276d0c1a43868a5a716633836cdd247416c2/img/df%20exp%202%20(5).png)

   - Use **Deeper Search** if needed. 
    ![alt text](https://github.com/saravanakannana/digital-forensics-experiments-2025/blob/3fff276d0c1a43868a5a716633836cdd247416c2/img/df%20exp%203%20(6).png)
 

**Access Advanced Options**  
   - Go to **Advanced → File System Utilities**. 
    ![alt text](https://github.com/saravanakannana/digital-forensics-experiments-2025/blob/3fff276d0c1a43868a5a716633836cdd247416c2/img/df%20exp%202%20(7).png)

   - Select the partition where files were deleted.

   - Press **Enter** to view files.  
 

**Recover Deleted Files**  
   - Deleted files are shown in red. 
    ![alt text](https://github.com/saravanakannana/digital-forensics-experiments-2025/blob/3fff276d0c1a43868a5a716633836cdd247416c2/img/df%20exp%202%20(8).png)

   - Highlight a file and press **C** (copy) to recover. 
    ![alt text](https://github.com/saravanakannana/digital-forensics-experiments-2025/blob/3fff276d0c1a43868a5a716633836cdd247416c2/img/df%20exp%202%20(9).png)

   - Choose a **different drive** as the destination to avoid overwriting data.  
 

**Verify Recovered Files**  
   - Open the destination folder and check if the files were restored correctly.

   - Document the recovery in the log file.  

---

## Result  
Deleted or damaged files were successfully recovered from the storage device using TestDisk, and their integrity was preserved for forensic analysis.  

---
