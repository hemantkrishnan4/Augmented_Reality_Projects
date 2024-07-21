
# Augmented Reality Project

This project explores Augmented Reality (AR) and includes the creation of an AR Cube, Avatar, and Business Card. When the business card is clicked, it opens the corresponding website of my profile.

## Project Overview

- **AR Cube**: A virtual cube that can be interacted with in augmented reality.
- **AR Avatar**: A virtual avatar that appears in augmented reality.
- **AR Business Card**: A virtual business card that opens the corresponding website of my profile when clicked.

## Instructions for Combining Split Volumes

To use the files, you need to combine the following split volumes:

1. **Library/PackageCache/com.unity.burst@1.8.8/.Runtime/libburst-llvm-15.dylib**

   Combine these parts:
   - `Library/PackageCache/com.unity.burst@1.8.8/.Runtime/libburst-llvm-15.dylib.splitaa`
   - `Library/PackageCache/com.unity.burst@1.8.8/.Runtime/libburst-llvm-15.dylib.splitab`

2. **Library/ArtifactDB**

   Combine these parts:
   - `Library/ArtifactDB.splitaa`
   - `Library/ArtifactDB.splitab`
   - `Library/ArtifactDB.splited`

### How to Combine the Files

You can use the `cat` command on Unix-like systems (Linux, macOS) to combine the split files. Here’s an example of how to do it:

```sh
cat Library/PackageCache/com.unity.burst@1.8.8/.Runtime/libburst-llvm-15.dylib.splitaa \
    Library/PackageCache/com.unity.burst@1.8.8/.Runtime/libburst-llvm-15.dylib.splitab > \
    Library/PackageCache/com.unity.burst@1.8.8/.Runtime/libburst-llvm-15.dylib

cat Library/ArtifactDB.splitaa \
    Library/ArtifactDB.splitab \
    Library/ArtifactDB.splited > \
    Library/ArtifactDB
```

### Results

The Augmented Reality project successfully demonstrates the use of AR technology to create interactive virtual objects. The AR Cube and Avatar provide engaging 3D elements, while the AR Business Card offers a practical application by linking to an online profile.

Feel free to explore and interact with these AR elements to experience the possibilities of augmented reality!

Augmented Reality Business Card
![AR_Business_Card](https://github.com/user-attachments/assets/215a88d1-59e4-4901-ac43-c48ea35ef31a)

Augmented Reality Avatar
![AR_Avatar](https://github.com/user-attachments/assets/502d9405-2785-452a-8105-d7175267f5e7)

Augmented Reality Cube
![AR_Cube](https://github.com/user-attachments/assets/dad072dd-adef-46fb-a3e4-2a10eadf52ad)

## How to Run the Project

1. Clone the repository:
   ```sh
   git clone https://github.com/YOUR_USERNAME/NEW_REPOSITORY_NAME.git
   ```

2. Follow the instructions above to combine the split volumes.

3. Open the project in Unity to explore the AR Cube, Avatar, and Business Card.

## License

This project is licensed under the MIT License.

## Reference

This project was developed with the help of [this video tutorial](https://www.youtube.com/watch?v=WzfDo2Wpxks&t=33748s).



