# 🌌 Universe Database

This repository contains a **PostgreSQL database dump** for a structured representation of the universe, including galaxies, stars, planets, moons, and asteroids.

## 📂 Database Overview

The database consists of the following tables:

- **galaxy** – Stores galaxy data such as name, alias, diameter, and shape.
- **star** – Contains information about stars, including their name, associated galaxy, diameter, and color.
- **planet** – Represents planets, linking them to stars with a count of their moons.
- **moon** – Stores details about moons and their parent planets.
- **asteroid** – Contains asteroid data, including surface composition and type.

## 🔄 Restoring the Database

To restore this database from the dump file (`universe_dump.sql`), use the following command:

```sh
psql -U your_username -d your_database_name -f universe_dump.sql
```

## 📌 Future Enhancements  
• Add more celestial objects such as **comets** and **black holes**.
• Expand ```sh planet ``` table to include attributes like **orbital period** and **mass**.
• Implement stored procedures or triggers for automated data validation.

## 🤝 Contributing
Feel free to fork this repository, make improvements, and submit pull requests.  