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

Replace the placeholders with the relevant information:

- `{Reason for Service}` — reason why the service was requested (e.g., agendamento, transferência)
- `{Specialty}` — medical specialty involved (e.g., cardiologia, dermatologia)
- `{Type of Service}` — type of service scheduled (e.g., consulta, exame)
- `{include date and time}` — date and time when the service was scheduled

### Prompt (Revised):

`Replace the placeholders with the appropriate information indicated as X and generate a beneficiary service report in Portuguese. The report should state that the requester made contact to request {Reason for Service} related to the {Specialty} specialty, and that the {Type of Service} was scheduled for {include date and time}. The text must be written in a single paragraph and must not contain any personal data. Adjust the content as necessary, taking into account variations in the Reason for Service (e.g., Scheduling, Transfer, Cancellation, Network Referral) and in the Type of Service (e.g., Consultation, Exam), ensure the language remains clear, accurate, and professional throughout.`

## Example output

`O solicitante entrou em contato para solicitar o cancelamento relacionado à especialidade de Dermatologia, e o exame foi devidamente registrado conforme solicitado.`

## Contributing

Contributions to enhance prompt accuracy or add new scenarios are welcome via issues or pull requests.

## License

This project is licensed under the MIT License.
