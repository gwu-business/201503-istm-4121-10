# Midterm Exam Table Design

## Tables

### `songs`

id | title | artist_name | duration_milliseconds
--- | --- | --- | ---
1 | --- | --- | ---
2 | --- | --- | ---
3 | --- | --- | ---
4 | --- | --- | ---
5 | --- | --- | ---
6 | --- | --- | ---
7 | --- | --- | ---
8 | --- | --- | ---

<hr>

### `plays`

id | song_id | listener_id | started_playing_at | radio_station_id
--- | --- | --- | --- | ---
1 | --- | --- | --- | ---
2 | --- | --- | --- | ---
3 | --- | --- | --- | ---
4 | --- | --- | --- | ---
5 | --- | --- | --- | ---
6 | --- | --- | --- | ---
7 | --- | --- | --- | ---
8 | --- | --- | --- | ---

<hr>

### `thumbs`

id | play_id | thumb_type | thumb_pressed_at
--- | --- | --- | ---
1 | --- | --- | ---
2 | --- | --- | ---
3 | --- | --- | ---
4 | --- | --- | ---
5 | --- | --- | ---
6 | --- | --- | ---
7 | --- | --- | ---
8 | --- | --- | ---

<hr>

### `skips`

id | play_id | skipped_at
--- | --- | ---
1 | --- | ---
2 | --- | ---
3 | --- | ---
4 | --- | ---
5 | --- | ---
6 | --- | ---
7 | --- | ---
8 | --- | ---

<hr>

### `listeners`

id | full_name | email_address
--- | --- | ---
1 | Alyce Howe | alyce.howe@gmail.com
2 | Curt Kshlerin | curt_kshlerin@hotmail.com
3 | Carley Block | block.carley@hotmail.com
4 | Mozelle Aufderhar | aufderhar_mozelle@yahoo.com
5 | Lily Marie | lily.stiedemann@gwu.edu
6 | Felix Luettgen | elijah.luettgen@gwu.edu
7 | Andres the Mighty | andres.beahan@yahoo.com
8 | Rashad J | rash111@yahoo.com

<hr>

### `listener_accounts`

listener_id | cc_holder_name | cc_number | cc_exp_month | cc_exp_year | cc_zipcode | invoice_usd_per_day
--- | --- | --- | --- | --- | --- | ---
1 | Alyce Howe        | 111122222233333 | 01 | 2016 | 06405 | 0.00
2 | Curt Kshlerin     | 111122222233334 | 12 | 2020 | 20052 | 0.40
3 | Carley Block      | 88822222233335  | 11 | 2017 | 20037 | 0.40
4 | Mozelle Aufderhar | 111122222233336 | 10 | 2018 | 20001 | 0.00
5 | Lily M Stiedemann | 88822222233337  | 08 | 2015 | 20052 | 0.40
6 | Elijah Luettgen   | 111122222233338 | 03 | 2016 | 20037 | 0.00
7 | Andres Beahan     | 88822222233339  | 01 | 2015 | 20001 | 0.20
8 | Rashad Jones      | 111122222233340 | 07 | 2016 | 20052 | 0.20

<hr>