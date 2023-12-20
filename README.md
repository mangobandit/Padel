# Padel

# Clone the repository
git clone https://github.com/your-username/your-repository.git

# Navigate to the repository directory
cd your-repository

# Add a new file
echo digraph party_layout {
    node [shape=oval, style=filled, color=orange];
    edge [color=black];

    "Party Layout" -> "Court Layout";
    "Party Layout" -> "Facilities";
    "Party Layout" -> "Entertainment";
    "Party Layout" -> "Safety & Comfort";

    "Court Layout" -> "Playing Area";
    "Court Layout" -> "Seating";
    "Court Layout" -> "Decoration";

    "Facilities" -> "Catering Area";
    "Facilities" -> "Music Setup";
    "Facilities" -> "Lighting";

    "Entertainment" -> "MC or Host";
    "Entertainment" -> "Exhibition Matches";
    "Entertainment" -> "Interactive Games";

    "Safety & Comfort" -> "Emergency Access";
    "Safety & Comfort" -> "Heating/Cooling";
    "Safety & Comfort" -> "Sanitation";
}
 > padel_court_creation.dot

# Stage the new file
git add padel_court_creation.dot

# Commit the file
git commit -m "Add padel court creation mind map"

# Push the file to GitHub
git push origin master
