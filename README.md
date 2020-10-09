# pintando-paredes.py
Esse é um programa que te auxilia a pintar parede
larg = float (input('Digite a largura da parede:'))
alt = float (input('Digite a altura da parede:'))
área = larg * alt 
print (' sua parede tem a dimensão de {}x{} e a sua área é de {}m2'.format(larg, alt, área))
tinta = área / 15 
print ('para pintar pintar essa parede, vc precisará de {}L de tinta'.format(tinta))
