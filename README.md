Task1:



Check valid passwords:


Пароль 'password123' - вже використаний.

Пароль 'newpassword' - унікальний.

Пароль 'admin123' - вже використаний.

Пароль 'guest' - унікальний.


Check invalid password:

[123, '']:


Пароль '123' - пароль відсутній чи не є рядком.

Пароль '' - пароль відсутній чи не є рядком.


'password':

raise ValueError("Паролі мають бути передані списком.")
