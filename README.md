# Tasks & Triumphs: Habit Tracker

## General Information
**Tasks & Triumphs** is a habit tracker built on **Oracle APEX**, combining habit-forming principles with the excitement of role-playing games (RPGs). Users can track their habits while earning points based on different personal development dimensions: physical, emotional, social, intellectual, spiritual, vocational, and financial. These points allow users to face weekly challenges and bosses, creating an engaging self-improvement journey that makes each milestone feel like a victory.

The project was developed as part of **HackMTY** and focuses on personal growth through habit tracking and rewards. With Oracle APEX, we were able to design the interface, back-end systems, and databases that store user data and track progress.

## Features
- Create and manage personal habits
- Track progress in seven dimensions of personal development
- Earn points for habit completion
- Weekly boss challenges based on points earned
- User profile progression system

## Inspiration
We wanted to make personal growth fun, engaging, and motivating. By integrating RPG mechanics with habit tracking, **Tasks & Triumphs** turns self-improvement into a game, where each completed habit helps users level up in different areas of life.

## Getting Started

### Prerequisites
To run the project, you need access to:
- **Oracle APEX Project** [environment for deploying the application](https://apex.oracle.com/pls/apex/r/clayws/habits-tracker/home?session=124943118781751)
- A web browser to interact with the Oracle APEX user interface.
- Feel free to use the following user:
Username: A01707658@tec.mx
Password: MeQuitaronMiNavaja2024.

### Included Technologies
- **Oracle APEX**: For rapid development of the front-end interface and integration with the back-end.
- **SQL**: To manage the data storage and retrieval for user habits, stats, and tracking.
- **PL/SQL**: Custom functions and triggers to calculate points, manage user progress, and handle database operations.

## Database Structure
The `main.sql` file contains the database structure needed for the application. This includes:

- **Users Table**: Stores user profile information, such as username, email, and points in different dimensions.
- **Habits Table**: Contains details of user habits, including the type of habit, progress, and completion status.
- **Progress Table**: Tracks the user’s daily/weekly progress across the seven dimensions of development.
- **Boss Battles**: Stores data about weekly challenges and bosses faced by the users based on their habit completion.

## Testing

### Manual Testing
After setting up the application in Oracle APEX:
1. **Test Habit Creation**:  
   Ensure users can create new habits, set goals, and track progress.
2. **Check Point System**:  
   Complete a habit and confirm that the points are awarded in the correct dimension of development.
3. **Weekly Boss Challenge**:  
   Test whether users can face weekly challenges based on their progress and points earned.
4. **Database Integrity**:  
   Check the database tables for correct data insertion and updates whenever a user interacts with the application.

## Future Features
We are excited to continue improving **Tasks & Triumphs**. Some features we plan to implement include:
- **Leaderboard**: Add a competitive leaderboard to track users' progress globally.
- **User Events**: Introduce events where users can compete in special challenges for extra points.
- **In-App Shop**: Allow users to redeem their points for rewards or digital items.
- **Interconnected Users**: Create a system where users can challenge each other or team up for co-operative goals.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
