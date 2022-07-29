This Calculation will Break Apart your 1Rep Max into 2,4,6,8,10
See this code:
!cmd add !rm_1 $(sender), 1 RM $(1:) = 10x ${customapi.https://decapi.me/math?exp=$(queryencode $(1:))*0.75&round=0} or 8x ${customapi.https://decapi.me/math?exp=$(queryencode $(1:))*0.80&round=0} or 6x ${customapi.https://decapi.me/math?exp=$(queryencode $(1:))*0.85&round=0} or 4x ${customapi.https://decapi.me/math?exp=$(queryencode $(1:))*0.90&round=0} or 2x ${customapi.https://decapi.me/math?exp=$(queryencode $(1:))*0.95&round=0}
