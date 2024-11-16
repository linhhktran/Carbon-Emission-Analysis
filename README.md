# Carbon-Emission-Analysis

Objective: 

                                                                                                                                                                                                                                                                                                                                                                                                                                      

Table 'industry_group'
| id | industry_group                                                         | 
| -: | ---------------------------------------------------------------------: | 
| 1  | "Consumer Durables, Household and Personal Products"                   | 
| 2  | "Food, Beverage & Tobacco"                                             | 
| 3  | "Forest and Paper Products - Forestry, Timber, Pulp and Paper, Rubber" | 
| 4  | "Mining - Iron, Aluminum, Other Metals"                                | 
| 5  | "Pharmaceuticals, Biotechnology & Life Sciences"                       | 
| 6  | "Textiles, Apparel, Footwear and Luxury Goods"                         | 
| 7  | Automobiles & Components                                               | 
| 8  | Capital Goods                                                          | 
| 9  | Chemicals                                                              | 
| 10 | Commercial & Professional Services                                     | 
| 11 | Consumer Durables & Apparel                                            | 
| 12 | Containers & Packaging                                                 | 
| 13 | Electrical Equipment and Machinery                                     | 
| 14 | Energy                                                                 | 
| 15 | Food & Beverage Processing                                             | 
| 16 | Food & Staples Retailing                                               | 
| 17 | Gas Utilities                                                          | 
| 18 | Household & Personal Products                                          | 
| 19 | Materials                                                              | 
| 20 | Media                                                                  | 
| 21 | Retailing                                                              | 
| 22 | Semiconductors & Semiconductor Equipment                               | 
| 23 | Semiconductors & Semiconductors Equipment                              | 
| 24 | Software & Services                                                    | 
| 25 | Technology Hardware & Equipment                                        | 
| 26 | Telecommunication Services                                             | 
| 27 | Tires                                                                  | 
| 28 | Tobacco                                                                | 
| 29 | Trading Companies & Distributors and Commercial Services & Supplies    | 
| 30 | Utilities                                                              | 

Table 'companies'
| id  | company_name                                   | 
| --: | ---------------------------------------------: | 
| 1   | "Autodesk, Inc."                               | 
| 2   | "Casio Computer Co., Ltd."                     | 
| 3   | "Cisco Systems, Inc."                          | 
| 4   | "CNX Coal Resources, LP"                       | 
| 5   | "Coca-Cola Enterprises, Inc."                  | 
| 6   | "Compañía Española de Petróleos, S.A.U. CEPSA" | 
| 7   | "Daikin Industries, Ltd."                      | 
| 8   | "Elitegroup computer systems co., Ltd."        | 
| 9   | "Fuji Xerox Co., Ltd."                         | 
| 10  | "Gamesa Corporación Tecnológica, S.A."         | 
| 11  | "Hino Motors, Ltd."                            | 
| 12  | "Hitachi, Ltd."                                | 
| 13  | "Interface, Inc."                              | 
| 14  | "Konica Minolta, Inc."                         | 
| 15  | "Kuraray Co., Ltd."                            | 
| 16  | "Lexmark International, Inc."                  | 
| 17  | "Mitsubishi Gas Chemical Company, Inc."        | 
| 18  | "Mitsui Mining & Smelting Co., Ltd."           | 
| 19  | "Osaka Gas Co., Ltd."                          | 
| 20  | "PepsiCo, Inc."                                | 
| 21  | "Ricoh Co., Ltd."                              | 
| 22  | "Shaw Industries Group, Inc."                  | 
| 23  | "Stanley Black & Decker, Inc."                 | 
| 24  | "Staples, Inc."                                | 
| 25  | "Toppan Printing Co., Ltd."                    | 
| 26  | "Yokohama Rubber Company, Limited"             | 
| 27  | "YONYU Plastics (Shanghai) Co.,Ltd"            | 
| 28  | Acbel Polytech Inc                             | 
| 29  | Agraz                                          | 
| 30  | Air Liquide                                    | 
| 31  | Ajinomoto Co.Inc.                              | 
| 32  | Akzo Nobel                                     | 
| 33  | Alcoa Corp.                                    | 
| 34  | Arcelor Mittal                                 | 
| 35  | Associated British Foods                       | 
| 36  | AVK                                            | 
| 37  | Azbil Corporation                              | 
| 38  | Barilla Holding SpA                            | 
| 39  | BillerudKorsnäs                                | 
| 40  | BlackBerry Limited                             | 
| 41  | Bloomberg                                      | 
| 42  | BORMIOLI LUIGI                                 | 
| 43  | Brambles                                       | 
| 44  | Braskem S/A                                    | 
| 45  | Bridgestone Corporation                        | 
| 46  | BT Group                                       | 
| 47  | Bumble Bee Foods LLC                           | 
| 48  | Cabot Corporation                              | 
| 49  | Canon Inc.                                     | 
| 50  | Cargill                                        | 
| 51  | CartOne S.r.l.                                 | 
| 52  | Chunghwa Picture Tubes Ltd                     | 
| 53  | CJ Cheiljedang                                 | 
| 54  | Clariant AG                                    | 
| 55  | CNX Resources                                  | 
| 56  | Coca-Cola HBC AG                               | 
| 57  | Compal Electronics                             | 
| 58  | CONTRAF-NICOTEX-TOBACCO GmbH                   | 
| 59  | Coway Co Ltd                                   | 
| 60  | Crimidesa                                      | 
| 61  | Daimler AG                                     | 
| 62  | Danone                                         | 
| 63  | Darfon Electronics Corp                        | 
| 64  | Dell Inc.                                      | 
| 65  | Delta Electronics                              | 
| 66  | DRAGON WILL ENTERPRISE                         | 
| 67  | Electrolux                                     | 
| 68  | Empresas CMPC                                  | 
| 69  | Fabrica de Tapas Bavaria                       | 
| 70  | Fujitsu Ltd.                                   | 
| 71  | General Motors Company                         | 
| 72  | Georg Fischer                                  | 
| 73  | Herman Miller                                  | 
| 74  | Hewlett-Packard                                | 
| 75  | Holmen                                         | 
| 76  | Humanscale Corporation                         | 
| 77  | HUMAX ELECTRONICS CO LTD                       | 
| 78  | Ingenico                                       | 
| 79  | Innolux Corporation                            | 
| 80  | Intel Corporation                              | 
| 81  | Johnson Matthey                                | 
| 82  | Kellogg Company                                | 
| 83  | KNOLL INC                                      | 
| 84  | Lafarge S.A.                                   | 
| 85  | Levi Strauss & Co.                             | 
| 86  | LG Chem Ltd                                    | 
| 87  | LG Electronics                                 | 
| 88  | Logitech International SA                      | 
| 89  | MAGOTTEAUX                                     | 
| 90  | Martin Bauer GmbH                              | 
| 91  | Maxxis International                           | 
| 92  | MediaTek                                       | 
| 93  | Metsä Board                                    | 
| 94  | MI (Michaelleides)                             | 
| 95  | Miquel Y Costas                                | 
| 96  | MITIE Group                                    | 
| 97  | Molson Coors Brewing Company                   | 
| 98  | Motorola Mobility                              | 
| 99  | Mpact Limited                                  | 
| 100 | MUNTONS PLC                                    | 
| 101 | NCP ALCOHOLS                                   | 
| 102 | NEC Corporation                                | 
| 103 | Nestlé                                         | 
| 104 | Nokia Group                                    | 
| 105 | OMRON Corporation                              | 
| 106 | Owens-Illinois                                 | 
| 107 | Pacific Coast Producers                        | 
| 108 | Perfection Bakeries Inc.                       | 
| 109 | Philips & Lite-On Digital Solutions Corp.      | 
| 110 | PT Fajar Surya Wisesa Tbk                      | 
| 111 | PURECIRCLE USA                                 | 
| 112 | Qisda                                          | 
| 113 | Quanta Computer                                | 
| 114 | Quanta Storage Inc.                            | 
| 115 | Radius Systems                                 | 
| 116 | Raizen                                         | 
| 117 | Retal                                          | 
| 118 | Sanden                                         | 
| 119 | Sappi                                          | 
| 120 | Schneider Electric                             | 
| 121 | SGD Group                                      | 
| 122 | SHENYANG DONGRUI                               | 
| 123 | SK Hynix                                       | 
| 124 | Smurfit Kappa Group PLC                        | 
| 125 | Solvay S.A.                                    | 
| 126 | Steelcase                                      | 
| 127 | Stonyfield Farm Inc                            | 
| 128 | SunPower Corporation                           | 
| 129 | Syngenta AG                                    | 
| 130 | Tata Chemicals                                 | 
| 131 | Tata Steel                                     | 
| 132 | Tata Steel Europe                              | 
| 133 | Technicolor SA                                 | 
| 134 | Tennant Company                                | 
| 135 | TETRA PAK                                      | 
| 136 | Times Microwave Systems                        | 
| 137 | Trelleborg AB                                  | 
| 138 | Trinseo LLC                                    | 
| 139 | Volkswagen AG                                  | 
| 140 | Waters Corporation                             | 
| 141 | Weg S/A                                        | 
| 142 | Wistron Corp                                   | 
| 143 | WOLF                                           | 
| 144 | Xerox Corporation                              | 
| 145 | ZHEJIANG WANFENG AUTO WHEEL CO LTD             | 

Table 'countries'
| id | country_name   | 
| -: | -------------: | 
| 1  | Australia      | 
| 2  | Belgium        | 
| 3  | Brazil         | 
| 4  | Canada         | 
| 5  | Chile          | 
| 6  | China          | 
| 7  | Colombia       | 
| 8  | Finland        | 
| 9  | France         | 
| 10 | Germany        | 
| 11 | Greece         | 
| 12 | India          | 
| 13 | Indonesia      | 
| 14 | Ireland        | 
| 15 | Italy          | 
| 16 | Japan          | 
| 17 | Lithuania      | 
| 18 | Luxembourg     | 
| 19 | Malaysia       | 
| 20 | Netherlands    | 
| 21 | South Africa   | 
| 22 | South Korea    | 
| 23 | Spain          | 
| 24 | Sweden         | 
| 25 | Switzerland    | 
| 26 | Taiwan         | 
| 27 | United Kingdom | 
| 28 | USA            | 


data mining, lọc data
select *
from product_emissions
where upstream_percent_total_pcf not like '%N/A%'
group by id
having count(*) = 1



question 1
SELECT 
    product_name,
    SUM(carbon_footprint_pcf) AS total_emissions
FROM product_emissions
GROUP BY product_name
ORDER BY total_emissions DESC
LIMIT 10

| product_name                                                                                                                       | total_emissions | 
| ---------------------------------------------------------------------------------------------------------------------------------: | --------------: | 
| Wind Turbine G128 5 Megawats                                                                                                       | 3718044         | 
| Wind Turbine G132 5 Megawats                                                                                                       | 3276187         | 
| Wind Turbine G114 2 Megawats                                                                                                       | 1532608         | 
| Wind Turbine G90 2 Megawats                                                                                                        | 1251625         | 
| TCDE                                                                                                                               | 198150          | 
| Land Cruiser Prado. FJ Cruiser. Dyna trucks. Toyoace.IMV def unit.                                                                 | 191687          | 
| Retaining wall structure with a main wall (sheet pile): 136 tonnes of steel sheet piles and 4 tonnes of tierods per 100 meter wall | 167000          | 
| Electric Motor                                                                                                                     | 160655          | 
| Audi A6                                                                                                                            | 111282          | 
| Average of all GM vehicles produced and used in the 10 year life-cycle.                                                            | 100621          | 

question 2
SELECT 
    pe.product_name,
    ig.industry_group,
	SUM(pe.carbon_footprint_pcf) AS total_emissions
FROM product_emissions pe
LEFT JOIN industry_groups ig 
ON pe.industry_group_id = ig.id
GROUP BY pe.product_name, ig.industry_group
ORDER BY total_emissions DESC
LIMIT 10;

| product_name                                                                                                                       | industry_group                     | total_emissions | 
| ---------------------------------------------------------------------------------------------------------------------------------: | ---------------------------------: | --------------: | 
| Wind Turbine G128 5 Megawats                                                                                                       | Electrical Equipment and Machinery | 3718044         | 
| Wind Turbine G132 5 Megawats                                                                                                       | Electrical Equipment and Machinery | 3276187         | 
| Wind Turbine G114 2 Megawats                                                                                                       | Electrical Equipment and Machinery | 1532608         | 
| Wind Turbine G90 2 Megawats                                                                                                        | Electrical Equipment and Machinery | 1251625         | 
| TCDE                                                                                                                               | Materials                          | 198150          | 
| Land Cruiser Prado. FJ Cruiser. Dyna trucks. Toyoace.IMV def unit.                                                                 | Automobiles & Components           | 191687          | 
| Retaining wall structure with a main wall (sheet pile): 136 tonnes of steel sheet piles and 4 tonnes of tierods per 100 meter wall | Materials                          | 167000          | 
| Electric Motor                                                                                                                     | Capital Goods                      | 140647          | 
| Audi A6                                                                                                                            | Automobiles & Components           | 111282          | 
| Average of all GM vehicles produced and used in the 10 year life-cycle.                                                            | Automobiles & Components           | 100621          | 
