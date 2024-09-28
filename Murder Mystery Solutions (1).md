SELECT * 
FROM crime_scene_report
LIMIT 5;
![image](https://github.com/user-attachments/assets/fb96013c-cd26-497d-a7be-4fabb1b1cf83)

SELECT *
FROM crime_scene_report
WHERE type = "murder";

SELECT *
FROM crime_scene_report
WHERE type = "murder"
AND date = 20180115
AND city = "SQL City";
![image](https://github.com/user-attachments/assets/d786c6e4-14c6-4adb-8e1c-789c41d3a705)

SELECT *
FROM person
LIMIT 5;
![image](https://github.com/user-attachments/assets/e7eaa83a-3314-4846-aa4a-68efb4ba6438)

SELECT *
FROM person
WHERE address_street_name = "Northwestern Dr"
ORDER BY address_number DESC;
![image](https://github.com/user-attachments/assets/1105397b-894f-46ef-8103-494df0651407)

SELECT *
FROM person
WHERE name LIKE '%Annabel%'
AND address_street_name = "Franklin Ave";
![image](https://github.com/user-attachments/assets/54ae6281-cf6c-4307-b9c1-e0771e938aff)

SELECT *
FROM interview
WHERE person_id IN ("14887", "16371");
![image](https://github.com/user-attachments/assets/ebe8705d-aee4-41ac-8968-49457072cb86)

SELECT *
FROM get_fit_now_check_in
WHERE membership_id LIKE '48Z%'
AND check_in_date = "20180109";
![image](https://github.com/user-attachments/assets/f0cce56e-0ed7-455f-9cdf-31fd6dc74825)

SELECT *
FROM drivers_license
WHERE gender = "male"
AND plate_number LIKE '%H42W%';
![image](https://github.com/user-attachments/assets/37d818ca-6407-40a8-b349-6e30fa01f069)

SELECT *
FROM person
WHERE license_id IN ("423327", "664760");
![image](https://github.com/user-attachments/assets/cccae2ea-3feb-458f-95dc-88f75257ea27)

SELECT *
FROM get_fit_now_member
WHERE person_id IN ("51739", "67318");
![image](https://github.com/user-attachments/assets/6e017fad-3311-454b-a450-2ad0c6dad965)


![image](https://github.com/user-attachments/assets/6e7941e2-2b67-40b1-a9f9-fdd612e562a6)


