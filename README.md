%% Caso de Uso: Registro de Socios
%% -------------------------------
%% Actor y casos
actor Socio

Socio --> (Alta de Socio en Sede)
Socio --> (Recarga de Saldo)

%% Agrupación del caso “Registro de Socios”
rectangle "Registro de Socios" {
  (Alta de Socio en Sede)
  (Recarga de Saldo)
}
