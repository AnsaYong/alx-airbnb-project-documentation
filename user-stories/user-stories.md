### 1. User Registration

#### User Story:
As a user, I want to register an account so that I can access the platform's features, such as listing or booking properties.

#### Acceptance Criteria:
The registration form must validate input fields like email and password.
An error message is displayed if the email is already registered.
Upon successful registration, the user receives a confirmation email.

### 2. Property Listing

#### User Story:
As a property owner, I want to list my property on the platform so that users can view and book it.

#### Acceptance Criteria:
Property details such as title, price, location, and amenities must be provided.
Only authenticated users with the "host" role can list properties.
A success message confirms that the property is listed and visible to potential renters.

### 3. Search for Properties

#### User Story:
As a user, I want to search for properties based on location, price range, and amenities so that I can find a property that meets my needs.

#### Acceptance Criteria:
Users can search properties by location (required) and optionally filter by price and amenities.
Search results display the property title, price, location, and a thumbnail image.
An appropriate message appears if no properties match the search criteria.

### 4. Booking a Property

#### User Story:
As a user, I want to book a property for specific dates so that I can secure accommodation for my trip.

#### Acceptance Criteria:
The system checks for availability for the selected dates before confirming the booking.
Users receive a booking confirmation email upon success.
An error message is displayed if the property is not available for the selected dates.

### 5. Payment for Bookings

#### User Story:
As a user, I want to securely pay for my booking so that I can confirm my reservation.

#### Acceptance Criteria:
Payments can be made via credit/debit cards or other supported payment methods.
The system verifies payment success and generates a transaction ID.
Users are notified if the payment fails, with a reason provided (e.g., insufficient funds).

### Additional Stories (Optional)

#### 1. Notifications:
As a user, I want to receive notifications about my bookings so that I stay informed about updates or changes.

#### 2. Reviews and Ratings:
As a user, I want to leave a review and rating for a property I stayed in so that I can share my experience with others.
