# Croc Tales: Education and Adventure

Project for GovHack 2024. Northern Territory Challenges:
1. How can data be leveraged to create innovative solutions that boost tourism in the Northern Territory, attract more visitors, and/or enhance their cultural experience?
2. Crocodile Watch: Enhancing Public Safety

**Croc Tales: Education and Adventure** is an interactive tourism and education initiative aimed at promoting public safety and increasing engagement with the Northern Territory’s (NT) rich wildlife and cultural heritage. Inspired by the success of Wrocław’s gnome statues, this project features crocodile statues scattered across NT cities, integrated with an interactive mobile-friendly web app. The app encourages users to explore NT, learn about Crocwise safety measures, and unlock fun rewards as they discover each statue.

---

### **Key Features**:

1. **Croc Statues**:  
   - A series of crocodile statues placed in key tourist and culturally significant locations across NT.
   - Each croc statue will have a unique design, symbolizing local culture or a **Crocwise** educational message.
   - QR codes integrated into the crocodile skin pattern, which can be scanned to reveal a story about the location.

2. **Web App (React.js-based)**:  
   - **Camera QR Scanner**: Users scan QR codes at the statues to unlock stories and progress through the game.
   - **Quiz System**: Users answer questions based on **Crocwise** safety tips to unlock the next crocodile statue location on the map.
   - **Interactive Map**: Shows the user's current location and nearby crocodile statues to visit.
   - **Achievements & Badges**: Users can unlock and share achievements as they visit statues and complete quizzes.
   - **Social Media Integration**: Users can share their achievements and crocodile-themed photo frames on social media platforms.
   - **Crocwise Education**: Integrated educational tips and fun facts about crocodile safety at each stage.

---

### **Data Sources & Integration**:

1. **Territory Stories** (https://territorystories.nt.gov.au/)  
   - Historical and cultural content about the locations of the statues, pulled into the app to enrich the visitor experience.

2. **Northern Territory Tourism Data** (https://northernterritory.com/)  
   - Tourism insights, visitor guides, and location-based recommendations integrated into the app to encourage broader exploration.

3. **Latest Visitor Data** (https://tourismnt.com.au/research-strategies/research/latest-visitor-data)  
   - Real-time visitor insights help determine optimal placements for the statues and improve user engagement with high-traffic tourist spots.

 4. **NT Crocodile Capture Zones and Daily Count**  [NT Crocodile Capture Zones and Daily Count](https://data.nt.gov.au/dataset/nt-crocodile-capture-zones-and-daily-count)  
   **Integration**:  
   - **Real-Time Crocodile Data**: This dataset provides information on crocodile capture zones and daily counts, which can be integrated into the app to inform users about the latest crocodile activity in various zones.  
   - **Interactive Map**: The real-time data can be displayed on the **Explore** map, allowing users to see areas with recent crocodile captures, helping raise awareness about croc-prone areas in real time.  
   - **Crocwise Alerts**: Based on high activity in certain zones, the app can push Crocwise safety alerts to users in proximity to those areas.

5. **Crocodile Monitoring Survey**  [Crocodile Monitoring Survey](https://data.nt.gov.au/dataset/crocodile-monitoring-survey)  
   **Integration**:  
   - **Crocodile Population Insights**: This survey dataset includes monitoring information about crocodile populations across different regions.  
   - **Educational Content**: The app can use this data to educate users about population trends in specific areas, providing context on why Crocwise education is critical.
   - **Location-Based Insights**: Users visiting areas with higher crocodile populations will receive additional Crocwise safety messages based on the data.

By integrating these datasets, the app can deliver more **real-time safety information** and **educational insights**, making it an even more engaging and informative tool for both tourists and locals.

---

### **Statue Themes and Ideas**:

Drawing inspiration from Wrocław's creative gnome statues, here's a list of **crocodile statue ideas** for the **Croc Tales: Education and Adventure** project. Each croc statue incorporates elements of **Crocwise education** while representing different aspects of NT's culture, history, and wildlife.

### 1. **Explorer Croc**
- **Location**: Darwin Waterfront
- **Design**: A crocodile dressed as an adventurer with a backpack, map, and binoculars, gazing over the water.
- **Crocwise Lesson**: “Always stay at least 5 meters away from the water’s edge.”
- **Story**: This croc represents the spirit of exploration and the importance of being cautious near water bodies.

### 2. **Lifeguard Croc**
- **Location**: Mindil Beach
- **Design**: A crocodile wearing lifeguard gear, complete with sunglasses, a whistle, and a life buoy, sitting in a high chair overlooking the beach.
- **Crocwise Lesson**: “Never swim in rivers, creeks, or beaches where crocodiles may live.”
- **Story**: This croc educates visitors about water safety and the importance of swimming in designated areas.

### 3. **Farmer Croc**
- **Location**: Katherine Outback Heritage Museum
- **Design**: A crocodile dressed as a farmer with a hat, boots, and a shovel, working near the water with a fence nearby.
- **Crocwise Lesson**: “Keep livestock and pets away from the water’s edge to prevent attacks.”
- **Story**: This croc symbolizes the connection between agriculture and wildlife management in NT.

### 4. **Croc Ranger**
- **Location**: Kakadu National Park entrance
- **Design**: A crocodile in ranger uniform holding binoculars, with a sign that reads "Crocodile Territory."
- **Crocwise Lesson**: “Observe warning signs and never ignore crocodile danger zones.”
- **Story**: Represents the park rangers who help protect both tourists and crocodiles, ensuring a safe environment.

### 5. **Fisherman Croc**
- **Location**: Daly River
- **Design**: A crocodile holding a fishing rod, with a boat nearby and a bucket full of fish.
- **Crocwise Lesson**: “Always be cautious when fishing, and don’t clean fish near the water’s edge.”
- **Story**: This croc educates fishermen about safe practices when fishing in crocodile territory.

### 6. **Croc Doctor**
- **Location**: Royal Darwin Hospital
- **Design**: A crocodile dressed as a doctor with a stethoscope and a medical kit, checking another animal patient.
- **Crocwise Lesson**: “If bitten by a crocodile, seek medical attention immediately.”
- **Story**: Represents the importance of first aid and emergency response after a crocodile encounter.

### 7. **Bush Croc**
- **Location**: Litchfield National Park
- **Design**: A crocodile in bush gear with a wide-brimmed hat and hiking boots, carrying a walking stick and a water bottle.
- **Crocwise Lesson**: “Be aware of crocodiles while hiking near rivers or billabongs.”
- **Story**: This croc emphasizes staying cautious while hiking near water bodies where crocs may reside.

### 8. **Croc Photographer**
- **Location**: East Point Reserve
- **Design**: A crocodile holding a camera, ready to take a wildlife photo, with a bird perched nearby.
- **Crocwise Lesson**: “Always stay in designated safe viewing areas when watching wildlife.”
- **Story**: This croc promotes responsible wildlife watching and safety for photographers in NT.

### 9. **Diver Croc**
- **Location**: Nitmiluk Gorge
- **Design**: A crocodile wearing diving gear, mask, snorkel, and flippers, next to a sign saying “Do not enter the water.”
- **Crocwise Lesson**: “Never enter water without checking for crocodile risks.”
- **Story**: This croc emphasizes safety awareness before engaging in water activities in croc-prone areas.

### 10. **Croc Farmer**
- **Location**: Crocodylus Park, Darwin
- **Design**: A crocodile tending to a group of baby crocs in a protected enclosure, wearing a hat and holding a bucket of food.
- **Crocwise Lesson**: “Crocodile farms help conserve crocodile populations and manage risks.”
- **Story**: This croc educates visitors on the role of crocodile farms in conservation and sustainable crocodile management.

### 11. **Croc Pilot**
- **Location**: Darwin International Airport
- **Design**: A crocodile dressed as a pilot, with aviator sunglasses and a captain’s hat, standing next to a luggage cart.
- **Crocwise Lesson**: “Be Crocwise from the moment you arrive in NT.”
- **Story**: This croc welcomes visitors to NT and reminds them that Crocwise education begins as soon as they arrive.

### 12. **Storyteller Croc**
- **Location**: Alice Springs Desert Park
- **Design**: A crocodile sitting around a campfire with indigenous elders, telling a story to children.
- **Crocwise Lesson**: “Crocodiles play a vital role in the ecosystem and have deep cultural significance.”
- **Story**: Represents the indigenous connection to crocodiles and how they are revered in storytelling and cultural traditions.

### 13. **Croc Canoeist**
- **Location**: Mataranka Hot Springs
- **Design**: A crocodile paddling a canoe down the river, with a life jacket on and a smile.
- **Crocwise Lesson**: “Never paddle or canoe near crocodile habitats unless you know it’s safe.”
- **Story**: Educates visitors on safe practices for canoeing or kayaking in NT’s rivers.

### 14. **Croc Teacher**
- **Location**: Local NT schools (e.g., Darwin Middle School)
- **Design**: A crocodile in a teacher’s outfit, pointing to a blackboard with a Crocwise safety tip written on it.
- **Crocwise Lesson**: “Learn Crocwise early, and share it with your family and friends.”
- **Story**: This croc emphasizes the importance of teaching crocodile safety to the younger generation.

### 15. **Croc Magician**
- **Location**: Darwin Festival Grounds
- **Design**: A crocodile dressed as a magician, pulling a rabbit out of a hat, with a magic wand in hand.
- **Crocwise Lesson**: “Crocodiles may look slow on land, but they can surprise you with their speed.”
- **Story**: This croc reminds visitors not to be fooled by the crocodile’s calm appearance—they are fast and dangerous predators.

---

These crocodile statues will not only attract tourists but also serve an educational purpose, blending **Crocwise** safety lessons with engaging and culturally significant stories. Each statue can be accompanied by a QR code that, when scanned, provides more detailed stories, fun facts, and additional Crocwise tips.

---

### **App Structure (React.js)**:

#### **Main Components**:
- **Header.js & Footer.js**: Navigation and footer with essential links.
- **QuizCard.js**: Displays Crocwise questions and answer options.
- **AchievementBadge.js**: Represents earned achievements and badges.
- **CrocCard.js**: Shows the story and details of each croc after QR scanning.
- **Map.js**: Displays the interactive map with croc locations.
- **QRScanner.js**: Enables users to scan QR codes using the device camera.

#### **Pages**:
- **Home.js**: Introduction to the app and key buttons for exploration.
- **Explore.js**: Interactive map with croc statues and location info.
- **Quiz.js**: Quizzes that unlock new croc locations after answering correctly.
- **CrocStory.js**: Reveals the cultural story tied to the location.
- **Achievements.js**: Displays user achievements, badges, and milestones.

---

## Additional ideas
### **Social Sharing and Photo Frames**:

1. **Achievements Sharing**:  
   - Users can share their unlocked achievements and badges directly to social media platforms like Facebook, Instagram, or Twitter.
   - Pre-generated messages with hashtags like #CrocTalesNT, #CrocwiseSafety.

2. **Photo Frames**:  
   - Croc-themed photo frames available after visiting statues or completing quizzes.  
   - Users can customize the photo with text and download or share it on social media.

---

### **App Flow**:

1. **Start Adventure**: Users are introduced to the app and given a map with the first unlocked crocodile statue location.
2. **Visit and Scan**: Users scan the QR code at a statue, unlocking Crocwise safety information and a local story.
3. **Complete Quiz**: Users complete a Crocwise quiz related to the statue to unlock the next croc location.
4. **Achievements & Sharing**: Users collect digital badges and can share their progress or photos on social media.
5. **Explore More Locations**: Users continue exploring NT by visiting more croc statues, scanning, learning, and unlocking new locations.

---

### **Technical Feasibility**:

- **Web App**: Built using React.js with a mobile-first responsive design.
- **QR Code Scanning**: Integrated using the `getUserMedia()` API and libraries like `jsQR`.
- **Interactive Map**: Google Maps or OpenStreetMap can be used to guide users to croc locations.
- **Social Media Sharing**: Use libraries like `react-share` for easy integration with social platforms.
- **Custom Frames**: HTML5 Canvas API and libraries like `react-photo-editor` for custom croc-themed photo frames.

---

This project offers a fun, educational, and safety-focused experience while promoting the Northern Territory's unique cultural and wildlife heritage. The blend of gamified exploration, **Crocwise** education, and social media engagement will make it an unforgettable adventure for both tourists and locals.


# TODO
- Code of conduct
- ReactJs Firebase auth boilerplate
