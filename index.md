# [Modulární-úřad](https://github.com/modularni-urad)

> Každý trvale udržitelný software je modulární.
Modularita je to, co zoufale chybí software ve samosprávách.
A je to právě modularita, co je tím hlavním atributem projektů modulárního-úřadu.

Modul je malá komponenta, která:
- dělá přesně to, co má a nic navíc. 
- je deployovatelná jako docker container, tudíž řešení se dá orchestrovat např. pomocí [kubernetes](https://kubernetes.io/).
- nabízí API - ovládaní přes web applikaci, možnost napsat aplikace na telefon, integrovatelnost.

S pomocí dalších otevřených modulů, tovoří logický celek.
[Schéma modulů](https://github.com/modularni-urad/modularni-urad.github.io/blob/master/doc/architecture.plant) je na obrázku:

![Schema modulů](http://www.plantuml.com/plantuml/svg/ZLJFRji-3BxhAOYUVZtar-jG34EpPIY2TblMF-XXwO6LMKUjBNaItQ0P-Z1zW3t2JdcnoRBaEd63DSZ193z-7qMAEdACbkko4Aou82XDLXTejHhL5ZCOjGw2J65kiHG29HiBuwnKEdv_KgnMf8NG9YFO2o6uefjnLUq1Ei0bmYy1_lTZXcS6i05SjuuBTFSR3iCBigqdIhjhyPIuerIVNMwoHvhZpzzWXfQLL1LAwfDlqCh2r1bCDPFLn9ueINsTZaM6Z3Vel6xjoCvrieFkfNTDFgR2JjwTWongvtdsOZbjOAfpIywNQJHRKv0DoQhrHcIexG0hTL2XDTSDGEU-UhCLpSbu0AigGex9p8AzXSEQ5n4ozfzRKVOjBr57m4Lh1SnJh-uc4IP6tgS3HOfnucv41bbXliEi40pZ2QdDALCqyJPqKAeiAsY9bZg9BrSRZNWQIFf9jqtOgTiX0ccUclRs2ePz7fOH-_XQosQFl30Q8YBmnXdq2cK2g_85WxdTYARVYIaheqdp8nGhWigjdta3eE01xfHU_v4BkCFLerp_bY-Z9vq5aU74ZEFSqYjrfzlUOSw_duRBMmLpI7L6cNAGxIQo3M3pp0NTXYDteUvtAHVcOVti_-38EMMqstKQlxFjepFAp5AFFZGlZaXFHV99x_F-pauxB-HhplIH8cbZXMWtC_d3NJu4IpzhSWnBnOkvZlLE9tCjZRbN97gxscNcoVEMz7IzKZAtzbjImoQdlB2r63nrvUqsV0Z3HEodXV5u51jBhfCH_f64KMGz1ALl3Qmy0McsM6WbVKMMSkNOrg9zBtlmUgKUaAcWkVvFOsN_XnMSJiQpVI5U5X_UZv9u5FNesbC5jNsnjQ3_WekgFxjqaRj932AnpJlzIKuSaSxgilWB)
Na schéma byl použit [plantuml-previewer](https://sujoyu.github.io/plantuml-previewer/) <3
