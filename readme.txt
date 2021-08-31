This is 'hello world' repository.
這是用來練習Git也是用來介紹自己的儲存庫，
不然用真的專案來練習實在太可怕，
感覺一不小心就弄壞了。



        -xeach({3}, div((
                parm(temp, ?),
                temp= ?,br(),
				parm(equal_index?,:parm_indexof(?,Y)),
				if(!equal_index?(-1),
					div((
						parm(?_show, :parm_right(temp,:value(2+ :colparm(equal_index?)) )),
						?_show=, :colparm(?_show),br(),
						parm(?_col, :parm_left(temp, :colparm(equal_index?))),
 			       		equal_index?= , :colparm(equal_index?),br(),
					)),
				),
                concatparm(tr_row{4}, td(%:colparm(?_col)%), ),
        ))),
