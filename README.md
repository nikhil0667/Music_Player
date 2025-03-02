# **MEDIA PLAYER APP**  

**Company**: CODTECH IT SOLUTIONS  

**Name**: Khambhayta Nikhil Pravinbhai  

**Intern ID**: CT08VDB  

**Domain**: ANDROID DEVELOPMENT  

**Duration**: 4 WEEKS  

**Mentor**: NEELA SANTOSH  

I am currently working on a **Media Player App** as part of my internship project. This application is being developed for the **Android platform** using **Java** and follows the **Model-View-Controller (MVC)** architectural pattern. The primary goal of this app is to allow users to **play, pause, and navigate** through their local music files seamlessly while ensuring smooth UI interactions.

---

### **Key Features:**  
1. **Play, Pause, Next, Previous Controls:** Users can control audio playback with intuitive buttons.  
2. **Fetch Local Music Files:** The app scans the device’s storage and loads available music files.  
3. **Dynamic Playlist:** Users can see the list of available songs and select any song to play.  
4. **Background Playback:** Music continues to play even when the user exits the app.  
5. **User-Friendly UI:** A visually appealing design with easy-to-use controls.  

---

### **Technologies and Tools Used:**  
- **Android Development (Java):** The app is built using **Java** in **Android Studio**.  
- **MediaPlayer API:** Used for handling music playback efficiently.  
- **RecyclerView:** To display the list of available songs dynamically.  
- **Room Database:** Used for saving user preferences like last played song and volume settings.  
- **Permissions Handling:** Ensures the app requests and manages storage permissions properly.  

---

### **Handling Permissions for Storage Access:**  
Since Android 11 (API level 30) introduced **Scoped Storage**, special permission handling is required. The app checks and requests storage permission as follows:  

1. **For Android 10 and Below:**  
   - Uses `READ_EXTERNAL_STORAGE` permission to access local media files.  

2. **For Android 11 and Above:**  
   - Requests `MANAGE_EXTERNAL_STORAGE` permission to get full access to music files.  
   - Redirects users to **Settings** if permission is denied.  

---

### **Challenges Faced and Solutions:**  
**1. Permission Handling Issues**  
- Issue: Some devices did not grant permission automatically.  
- Solution: Implemented `shouldShowRequestPermissionRationale()` to handle cases where users deny permission and need manual activation.  

**2. Audio Playback in Background**  
- Issue: Music stopped when the app was minimized.  
- Solution: Used `Foreground Service` to keep playback running in the background.  

**3. Loading Large Music Libraries Efficiently**  
- Issue: Slow loading of songs when scanning large storage.  
- Solution: Used a **separate thread (AsyncTask)** to scan and load music files asynchronously.  

---

### **Unique Implementation Approaches:**  
- Implemented **custom notification controls** to allow play/pause directly from the notification panel.  
- Designed an **adaptive UI** that works on both phones and tablets.  
- Used **Kotlin Coroutines** to optimize performance and prevent UI freezing.  

---

### **Learning Outcomes:**  
Through this project, I have gained valuable knowledge in:  
- **Android Media Player API** for handling music playback.  
- **Permissions Handling** for different Android versions.  
- **Room Database** for saving user preferences.  
- **RecyclerView & ListAdapters** for smooth song list display.  

Additionally, I have improved my debugging skills and learned how to manage **foreground services** for background music playback.  

---

### **Conclusion:**  
This **Media Player App** is a significant step in my **Android Development** journey. The experience of handling **media playback, permissions, and background services** has strengthened my skills, preparing me for advanced mobile app development challenges.  

🚀 **This project has been a great learning experience, and I look forward to building more complex applications in the future.** 🎶

### **Output:**  
![Image](https://github.com/user-attachments/assets/fad87c98-cf9c-42d4-afa6-ae0081db54a5)
![Image](https://github.com/user-attachments/assets/5d26032e-ce9c-44c0-9847-cad2eba7cf23)
![Image](https://github.com/user-attachments/assets/a20d21cc-1498-4847-baf8-b952670f8ec4)
![Image](https://github.com/user-attachments/assets/e078eee1-b15d-425b-acf1-5d864595ba55)
![Image](https://github.com/user-attachments/assets/994dd5ca-c104-4b1f-940b-d2135591d9bc)
![Image](https://github.com/user-attachments/assets/6de11dfa-ba8d-471c-9ed3-71b09591a7ba)
![Image](https://github.com/user-attachments/assets/c1d18a54-d513-4210-b271-4c57a3ac54fa)
