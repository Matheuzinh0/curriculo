# Curriculo - Matheus Sousa

Repositorio contendo o codigo-fonte em LaTeX e a versao compilada em PDF do curriculo profissional e academico de Matheus Sousa, estruturado com foco em Ciberseguranca, Criptoanalise e Seguranca de Hardware/Firmware.

## Perfil de Atuacao

- Graduando em Engenharia de Telecomunicacoes pela Universidade Federal de Pernambuco (UFPE - 7o periodo).
- Tecnico em Analise e Desenvolvimento de Sistemas (ETE-SWC).
- Pesquisador de Iniciacao Cientifica (PIBIC/CNPq) no Laboratorio de Comunicacao e Seguranca da Informacao (LCSI/UFPE).
- Principais competencias tecnicas:
  - Criptoanalise linear e diferencial de cifras de fluxo sobre aneis de inteiros.
  - Avaliacao adversarial, propagacao de diferencas, vieses estatisticos e analise espectral de Walsh.
  - Concepcao e sintese de primitivas criptograficas e PRNGs em FPGA (AMD Vivado, Intel Quartus Prime, Verilog, VHDL).
  - Implementacao de algoritmos criptograficos em C/C++ de alto desempenho e Python.
  - Firmware seguro de tempo real para microcontroladores (ESP32, STM32) e comunicacao sem fio critica.
  - Analise de trafego de redes (Wireshark) e infraestrutura de cluster Linux (Slurm).

## Estrutura do Repositorio

- `curriculo.tex`: Codigo-fonte em LaTeX modular e customizado.
- `foto.jpg`: Fotografia de perfil embutida no cabecalho do documento.
- `curriculo.pdf`: Versao compilada em PDF de duas paginas balanceadas.

## Instrucoes de Compilacao

Para compilar o documento localmente utilizando TeX Live, TinyTeX ou MacTeX:

```bash
pdflatex -interaction=nonstopmode curriculo.tex
```

### Dependencias LaTeX
- `inputenc` [utf8]
- `fontenc` [T1]
- `babel` [portuguese]
- `geometry`
- `graphicx`
- `hyperref`
- `enumitem`
- `titlesec`
- `xcolor`
- `amsmath`, `amssymb`

## Contato e Redes

- Email: matheushenriqueprojeto@gmail.com
- LinkedIn: https://www.linkedin.com/in/matheus-sousa-739893255/
- GitHub: https://github.com/Matheuzinh0
