# API Endpoints

The application provides the following endpoints:

## Token Management
* Login - `http://127.0.0.1:8000/api/token/login/`
* Refresh Token - `http://127.0.0.1:8000/api/token/refresh/`

## Menu Items
* Get All Menu Items - `http://127.0.0.1:8000/api/menu-items`
* Get a Specific Menu Item - `http://127.0.0.1:8000/api/menu-items/{menu-itemId}`

## Bookings
* Get All Bookings - `http://127.0.0.1:8000/api/bookings`
* Get a Specific Booking - `http://127.0.0.1:8000/api/bookings/{bookingId}`

## User Authentication and Management
* Get All Users - `http://127.0.0.1:8000/auth/users/`
* Get Current User Info - `http://127.0.0.1:8000/auth/users/me/`
* Confirm User - `http://127.0.0.1:8000/auth/users/confirm/`
* Resend Activation - `http://127.0.0.1:8000/auth/users/resend_activation/`
* Set User Password - `http://127.0.0.1:8000/auth/users/set_password/`
* Reset User Password - `http://127.0.0.1:8000/auth/users/reset_password/`
* Confirm Password Reset - `http://127.0.0.1:8000/auth/users/reset_password_confirm/`
* Set User Username - `http://127.0.0.1:8000/auth/users/set_username/`
* Reset User Username - `http://127.0.0.1:8000/auth/users/reset_username/`
* Confirm Username Reset - `http://127.0.0.1:8000/auth/users/reset_username_confirm/`
