# salud360-final
 Historia | Estado | Cobertura actual / brecha |


| HU-01 Registro de paciente (RF-01) | Cumple | Registro con datos personales, documento, fecha de nacimiento, EPS y validaciones básicas. |

| HU-02 Inicio de sesión (RF-02) | Cumple | Inicio de sesión con correo y contraseña. |

| HU-03 Recuperación de contraseña (RF-03) | Demo local | Hay un flujo con código visible en pantalla; no se envía por correo y no es recuperación segura. |

| HU-04 Verificación en dos pasos (2FA) (RF-04) | Demo local | Se puede activar un reto de código en el login; el código es fijo y visible, sin autenticador ni entrega segura. |

| HU-05 Edición de perfil y contacto (RF-05) | Parcial | Se editan nombre, apellido, teléfono y dirección; el correo y otros datos no se pueden actualizar. |



| HU-07 Consulta de especialidades, médicos y sedes (RF-07) | Demo local | Hay una lista estática y búsqueda por sedes; no está conectada al catálogo de agenda ni a ubicaciones reales. |


| HU-09 Solicitud de cita (RF-09) | Cumple | Se puede solicitar una cita eligiendo especialidad, profesional, fecha, hora y modalidad. |

| HU-10 Reprogramación y cancelación de citas (RF-10) | Cumple | Las citas activas se pueden reprogramar o cancelar. |

| HU-11 Confirmación de cita (RF-11) | Cumple | Se confirma una cita pagada y se genera un código de confirmación. |


| HU-13 Historial de citas (RF-13) | Cumple | «Mis citas» lista citas y permite filtrarlas por estado y buscarlas. |


| HU-15 Citas presenciales y de telemedicina (RF-15) | Parcial | Se elige modalidad presencial o virtual; no hay funciones de teleconsulta (por ejemplo, enlace o sala de video). |


| HU-31 Consulta de copagos y cuotas moderadoras (RF-31) | Demo local | Se informa que el cálculo no está disponible y se muestra un valor ilustrativo de cero, no cobrable. |

| HU-32 Pago en línea (RF-32) | Parcial | Hay un flujo de pago simulado/local y un contrato esperado para API; no se integra una pasarela real. |


| HU-34 Configuración de agenda del médico (RF-34) | Demo local | El médico guarda días, horas y sede; esto limita las franjas de agenda y se valida al solicitar/reprogramar citas localmente. |

 
