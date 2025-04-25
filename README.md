# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```bash
lsblk
```

```bash
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```

```bash
mmls ~/disk.img
```
```bash
sudo ls -lh disk.img
```
```bash
strings disk.img | less

```

## OUTPUT:
<img width="400" alt="image" src="https://github.com/user-attachments/assets/b0cf614d-2882-49a0-a062-ba0fa6d84093"/>


<img width="400" alt="image" src="https://github.com/user-attachments/assets/eb43876f-a202-461a-9265-89e4ea36b4ca"/>

<img width="400" alt="image" src="https://github.com/user-attachments/assets/1fc8e81f-12c1-4927-92ca-a4a0a500950e"/>

<img width="400" alt="image" src="https://github.com/user-attachments/assets/92658b19-6e77-4be4-b84b-767fae44c7aa"/>

<img width="400" alt="image" src="https://github.com/user-attachments/assets/4aff8fc4-e59c-475e-bdb2-658f15c67c50"/>

## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.
