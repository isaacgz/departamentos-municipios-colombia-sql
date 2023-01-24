# departamentos-municipios-colombia-sql

Tabla Departamentos
	[id] [bigint]
	[name] [nvarchar]
	[code] [nvarchar]
	[active] [nvarchar]
	[created_at] [datetime] 
	[updated_at] [datetime]
  
Tabla Municipios
  [id] [bigint] 
	[id_department] [bigint] (Llave foranea de departamentos)
	[name] [nvarchar]
	[code] [nvarchar]
	[active] [nvarchar]
	[created_at] [datetime] 
	[updated_at] [datetime] 


Departamentos y municipios relacionados.
