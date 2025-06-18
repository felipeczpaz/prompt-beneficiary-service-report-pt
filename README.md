# Beneficiary Service Report Generator (Portuguese) for dbm Contact Center - Grupo Amil

This repository contains a ChatGPT prompt designed specifically to generate beneficiary service reports in Portuguese for the dbm Contact Center client Grupo Amil. The reports summarize service requests clearly, accurately, and professionally in a single paragraph, ensuring no personal data is included.

## Features

- Tailored for dbm Contact Center operations supporting Grupo Amil.
- Generates reports in Portuguese for various service request reasons (e.g., agendamento, transferência, cancelamento, encaminhamento em rede).
- Supports different medical specialties.
- Adapts to multiple types of services (e.g., consulta, exame).
- Ensures professional, clear, and accurate language.
- Produces concise reports without personal or sensitive data.

## Usage

Fill the Protocol fields with the relevant information and Prompt ChatGPT with the Prompt + filled Protocolo de Atendimento

### Protocolo de Atendimento

```
Protocolo de Atendimento
- Solicitante:
- Beneficiário:
- Marca Óptica/CPF:
- E-mail:
- Telefone:

Motivo do Atendimento:
- Agendamento
- Transferência
- Cancelamento X
- Indicação de Rede
- Outros: ___________________________________________

Tipo de Atendimento:
- Consulta
- Exame X

Especialidade:
- Alergologia
- Anestesiologia
- Cardiologia
- Cirurgia Geral
- Cirurgia Plástica
- Dermatologia
- Endocrinologia
- Ginecologia e Obstetrícia
- Hematologia
- Infectologia
- Medicina de Família e Comunidade
- Medicina do Trabalho
- Medicina Esportiva
- Nefrologia
- Neurologia
- Oftalmologia
- Ortopedia
- Otorrinolaringologia
- Pediatria
- Pneumologia
- Psiquiatria
- Reumatologia
- Urologia
```

### Prompt (Revised):

```
Replace the placeholders with the appropriate information indicated as X and generate a beneficiary service report in Portuguese. The report should state that the requester made contact to request {Reason for Service} related to the {Specialty} specialty, and that the {Type of Service} was scheduled for {include date and time}. The text must be written in a single paragraph and must not contain any personal data. Adjust the content as necessary, taking into account variations in the Reason for Service (e.g., Scheduling, Transfer, Cancellation, Network Referral) and in the Type of Service (e.g., Consultation, Exam), ensure the language remains clear, accurate, and professional throughout.
```

## Example output

`O solicitante entrou em contato para solicitar o cancelamento relacionado à especialidade de Dermatologia, e o exame foi devidamente registrado conforme solicitado.`

## Contributing

Contributions to enhance prompt accuracy or add new scenarios are welcome via issues or pull requests.

## License

This project is licensed under the MIT License.
