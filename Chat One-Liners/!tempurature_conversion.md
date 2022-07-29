Weather Command
Looks like: !weather <City>
!command add !weather $(customapi.https://api.scorpstuff.com/weather.php?units=imperial&city=$(1:))


°C -> °F
!command add !temp_c $(sender), $(1:)°C ->  ${customapi.https://decapi.me/math?exp=$(queryencode $(1:))$(queryencode "*1.8+32")&round=1}°F


°F -> °C
!command add !temp_f $(sender), $(1:)°F -> ${customapi.https://decapi.me/math?exp=($(queryencode $(1:))-32)*5/9&round=1}°C