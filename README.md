# alistamento
#Programa lê se falta, se passou ou se está na hora de se alistar

ano = int(input('em que ano você nasceu?: '))
periodo = 2022 - ano
limite = 18 #idade de alistamento
atraso = periodo - limite
falta = ano - 2004


if periodo > limite:
    print(f'você está atrasado em {atraso} ano(s)')
elif periodo < limite:
    print(f'ainda faltam {falta} ano(s) para o seu alistamento')
else:
    print('está na hora de se alistar!!')
