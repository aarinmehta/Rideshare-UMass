# Rideshare UMass

**Rideshare UMass** is a web application specifically designed to help international and out-of-state students at the University of Massachusetts Amherst coordinate rideshares to and from Boston Logan Airport. The platform simplifies transportation logistics by connecting students with similar travel schedules, reducing costs and promoting sustainability through shared rides.

## Features

- **User Registration and Authentication**: Allows users to sign up, log in, and manage their profiles.
- **Trip Creation and Management**: Users can create trips by inputting their travel details, including the departure time, location, and destination.
- **Ride Matching**: The app automatically matches users with similar trips, helping them to coordinate rides efficiently.
- **Duplicate Trip Feature**: Users can duplicate trips with similar dates and routes, saving time for frequent travelers.
- **Public Dispatch Logs**: A public view of ride requests for transparency and easy coordination between passengers.
- **Pinned Messages**: Important messages related to rides can be pinned for easy access.

## Technologies Used

- **Frontend**: React.js, HTML, CSS
- **Backend**: Ruby on Rails, Node.js
- **Database**: PostgreSQL
- **Automated Testing**: RSpec
- **Version Control**: Git, GitHub

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/rideshare-umass.git
   ```
2. Navigate into the project directory:
   ```bash
   cd rideshare-umass
   ```
3. Install dependencies:
   ```bash
   bundle install
   npm install
   ```
4. Set up the database:
   ```bash
   rails db:create db:migrate
   ```

5. Start the server:
   ```bash
   rails server
   ```
6. Open your browser and navigate to `http://localhost:3000`.

## Usage

1. **Register**: Create a new user account and log in.
2. **Create a Trip**: Input your travel details, and the app will match you with others traveling at similar times.
3. **Join a Ride**: View available rides and join one that fits your schedule.
4. **Coordinate**: Use the app’s messaging system to finalize details with your fellow passengers.

## Contributions

We welcome contributions to enhance the functionality and usability of the Rideshare UMass app. To contribute, please:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and open a pull request.


