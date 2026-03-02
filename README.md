# ml-soccernet-keypoints

# Datensatzbeschreibung 
Der Datensatz "SoccerNet_Field_Keypoints“ enthält über 10’000 Einträge aus Fußball-Videodaten und wird für Computer-Vision-Aufgaben verwendet. Pro Zeile gibt es ein Bild eines Fußballfelds sowie dazugehörige Feld-Keypoints als Koordinatenlisten. Wichtige Felder sind "id“, "keypoints“ und „calibrated_keypoints“ sowie "is_bad“ oder "is good" für die kennzeichnung ob das Netz gut oder schlecht ist. Der Datensatz eignet sich, um die Qualität von Keypoint-Detektionen oder Kalibrierungen zu analysieren und vorherzusagen.

Datenschutz 
Der Datensatz betrifft Datenschutz nur begrenzt, da er primär Stadion-/Spielfeldaufnahmen und technische Annotationen (Keypoints) enthält und keine direkten personenbezogenen Angaben wie Namen, Adressen oder Kontaktdaten speichert. Dennoch können in Bildern theoretisch Personen sichtbar sein.Es werden keine zusätzlichen personenbezogenen Daten verknüpft, und im Repository wird nur eine kleine Demo-Datei ohne die eigentlichen Bilddaten abgelegt, um die Datenmenge zu reduzieren und Risiken zu minimieren. Die Quelle ist öffentlich zugänglich über Hugging Face.
