# Simulation-of-three-phase-induction-machine-using-Dynamic-Equation


![IM dynamic Equation](https://user-images.githubusercontent.com/35787202/126741561-86d10aad-9db5-4e6a-b99c-dcb2804f8e61.png)

Figure 1  (a) q axis model (b)d axis model of induction motor

Steady state model of induction motor can not simulate real world transient analysis. We simulated dynamic model of induction motor with analysis got from [4]. Electrical parameter of three phase frame is converted to synchronously rotating d-q frame (Fig.10). Then induction motor`s d and q axis parameters can be expressed using five following dynamic equations:
<img width="284" alt="eq1" src="https://user-images.githubusercontent.com/35787202/126741692-ddd7a1bb-dc34-4e94-a14f-1bf28e407f29.PNG">

Where , v_qs,v_ds,i_qs,i_ds=q,d axis stator voltage and q, d axis stator current , v_qr,v_dr,i_qr,i_dr= q, d axis rotor  voltage and q,d axis rotor current, ψqs,ψds=q,d axis stator flux, ψ_qr,ψ_dr=q,d axis rotor flux. ω_e=synchronous speed (rad/s), ω_r=rotor speed(rad/s), P=number of poles, J=moment of inertia, T_L=load torque, Te=electromagnetic Torque

From figure it is evident that,

<img width="284" alt="eq1" src="https://user-images.githubusercontent.com/35787202/126741777-654f21e3-fcff-4532-8650-a44e50468133.PNG">

<img width="418" alt="eq2" src="https://user-images.githubusercontent.com/35787202/126741821-b98440d3-10cd-43eb-9f46-782e9257a460.PNG">


where 
X_ls=ω_b L_ls,X_lr=ω_b L_lr,X_m=ω_b L_m

<img width="499" alt="eq3" src="https://user-images.githubusercontent.com/35787202/126741978-9d9a2afb-3e15-43d3-90b5-6758ee4139ee.PNG">

<img width="387" alt="eq4" src="https://user-images.githubusercontent.com/35787202/126742026-e2a3a4e8-f876-4115-abff-8de2ad47db09.PNG">

<img width="498" alt="eq5" src="https://user-images.githubusercontent.com/35787202/126742073-3de3e9e3-a7bc-4049-9fd5-286a618c1ec1.PNG">

<img width="467" alt="Simulink" src="https://user-images.githubusercontent.com/35787202/126742129-755467db-eab7-41c4-8f0a-731b106d4114.PNG">


## Simulation Result
![Simulation Result](https://user-images.githubusercontent.com/35787202/126743005-f043745d-81f0-4eb2-8737-d779da6b128c.jpg)




