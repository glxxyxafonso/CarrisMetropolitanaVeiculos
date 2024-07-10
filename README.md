# Todos os veículos da Carris Metropolitana.
Todos os veículos da Carris Metropolitana. 

Após descobrir que a Carris Metropolitana tem uma conta no GitHub, decidi ver mais sobre a API deles. Eventualmente, descobri o repo do website https://beta.carrismetropolitana.pt/. Neste repo, tinhamos a versão Production e Development (alpha). Durante uma pesquisa manual, descobri o arquivo info.json, dentro da pasta Veichles (que tinha uma imagem da FreePik com marca de água. Bad CM, bad cm...). A pasta tem, pelo menos parece-me, uma pasta com todos os veículos da Carris Metropolitana. 

Até agora, encontrei os seguintes operadores:
1. TST
2. Grupo Barraqueiro Transportes SA (Donos da Rodoviária de Lisboa e Barraqueiro Transportes)

Infelizmente, não consegui encontrar a VA nem o Alsa Todi.
Penso que esta lista só inclui os operadores que aderiram ao tracking da Carris Metropolitana.

Para finalizar,

AML, TST ou Barraqueiro Transportes: Não tenho nenhum problema em apagar este repo. Mas, se este repo for apagado, quero ver também o repo do site beta.carrismetropolitana.pt a ser privado ou apagado.

Obrigado,
Afonso :)

--- 

## Estrutura do arquivo, por isso, de cada autocarro.

    "agency_id": Identificador do operador.
    "vehicle_number": Número do veículo.
    "id": Junção dos dois IDs (agency_id, veichle_number)  agency_id|veichle_number
    "start_date": Começo da operação do veículo.
    "license_plate": Matrícula.
    "make": Marca do veículo. 
    "model": Modelo do Veículo. 
    "owner": Operador proprietário
    "registration_date": Data de registro do veículo (matrícula penso eu)
    "available_seats": Quantos lugares estão disponíveis
    "available_standing": Quantas pessoas podem ficar em pé no veículo (recomendação, penso eu)
    "typology": ??
    "vclass": ??
    "propulsion": ??
    "emission": Um rating de emissões, penso eu.
    "new_seminew": Se o veículo é seminovo (usado)
    "ecological": Se o veículo é elétrico ou não.
    "climatization": Se o veículo tem ar condicionado ou não. 
    "wheelchair": Se o veículo consegue ter um passageiro de cadeira de rodas.
    "corridor": Se tem um corredor? Não sei. 
    "lowered_floor": ??
    "ramp": Rampa ou sem rampa para passageiro de cadeira de rodas.
    "folding_system": Sistema de dobra, penso que da rampa. 
    "kneeling": ??
    "static_information": Se tem informação estática (por isso, um documento)
    "onboard_monitor": Se tem um ecrã dentro do autocarro, que diz a próxima paragem, etc.
    "front_display": Ecrã em frente do veículo (mostra nº do autocarro, etc.)
    "rear_display": Ecrã atrás do veículo (mostra nº do autocarro, etc.)
    "side_display": Ecrã ao lado do veículo (mostra nº do autocarro, etc.)
    "internal_sound": Se tem um speaker que diz a próxima paragem, etc.
    "external_sound": Coluna exterior?
    "consumption_meter": Provavelmente para medir o consumo de gasolina. 
    "bicycles": Lugares para bicicletas.
    "passenger_counting": Sistema de contagem de passageiros.
    "video_surveillance": Câmeras de segurança abordo.
