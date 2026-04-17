# Desarrollo

## Entregable 1

- Se cambia en .github/workflows/ci.yml de --cov-fail-under=50 a --cov-fail-under=70
- Se crea un nuevo rama git checkout -b feature/coverage-test 
- Se crea un entorno virtual python3 -m venv .venv
- Se usa pip install -r requirements-dev.txt para instalar las dependencias
- Se ejecuta python -m pytest -q --cov=prediction_pipeline_demo --cov-report=term-missing



======================================================= tests coverage =======================================================
______________________________________ coverage: platform linux, python 3.12.3-final-0 _______________________________________

Name                          Stmts   Miss Branch BrPart  Cover   Missing
-------------------------------------------------------------------------
prediction_pipeline_demo.py      25     11      2      1    56%   26-32, 36-37, 41, 44-49
-------------------------------------------------------------------------
TOTAL                            25     11      2      1    56%


================================================================ tests coverage ================================================================
_______________________________________________ coverage: platform linux, python 3.12.3-final-0 ________________________________________________

Name                          Stmts   Miss Branch BrPart  Cover   Missing
-------------------------------------------------------------------------
prediction_pipeline_demo.py      25      6      2      1    74%   44-49
-------------------------------------------------------------------------
TOTAL                            25      6      2      1    74%

## Entregable 2


## Entregable 3

Para ejecutar el runner local hay que poner los siguientes pasos:


cd /home/ovelez/Documentos/cursos/Maestria/Produccion/06-actions-runner/
./run.sh

Y volver a ejecutar desde los pipelines de github actions para ver los resultados en el runner local.