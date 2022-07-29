KG --> LB
!command add !kg @$(sender), I will now math your request. Beep Boop: $(1:) KG --> LB = ${customapi.https://decapi.me/math?exp=$(queryencode $(1:))*2.2046&round=1} --- KG --> Stone = ${customapi.https://decapi.me/math?exp=$(queryencode $(1:))/6.35029318&round=1}.


LB --> KG
!command add !lb @$(sender), I will now math your request. Beep Boop: $(1:) LB --> KG = ${customapi.https://decapi.me/math?exp=$(queryencode $(1:))/2.2046&round=1} --- LB --> Stone = ${customapi.https://decapi.me/math?exp=$(queryencode $(1:))/14&round=1}.


Stone --> LB and KG
!command add !stone @$(sender), I will now math your request. Beep Boop: $(1:) Stone --> LB = ${customapi.https://decapi.me/math?exp=$(queryencode $(1:))*14&round=1} --- Stone --> KG = ${customapi.https://decapi.me/math?exp=$(queryencode $(1:))*6.35029318&round=1}.