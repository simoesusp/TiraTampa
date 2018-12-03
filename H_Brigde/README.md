This is the description of a 12V H-Bridge circuit designed to AVOID short circuiting the output Mosfets.
It works based on the principle that Mosfet N would turn ON from 0.7V until Mosfet P turn off point at 11.3V.
All this time, the current between the Mosfets would be around 30A!!
The idea in this projet is to invert that input signal, so that Mosfet N will only turn ON from 0 to 0.7V and will turn OFF long before Mosfet P turn ON when input signal is higher than 11.3V.
The H-Bridge is very flexible: one can buy the output Mosfets according to the desired drive current and consequently cost of the project.

Please, refer also to this alternative: VNH2SP30
https://produto.mercadolivre.com.br/MLB-901487841-ponte-h-monster-motor-shield-vnh2sp30-30a-2-motor-_JM#reco_item_pos=0&reco_backend=machinalis-v2p&reco_backend_type=low_level&reco_client=vip-v2p&reco_id=828a4259-4dbf-4509-b115-ad99987264b7
