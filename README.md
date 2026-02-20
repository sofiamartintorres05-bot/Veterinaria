# Veterinaria
<?xml version="1.0" encoding="UTF-8"?>
<mxfile host="app.diagrams.net">
  <diagram name="Página-1" id="diagram1">
    <mxGraphModel dx="1026" dy="666" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>

        <!-- Entities -->
        <mxCell id="e_paciente" value="PACIENTE" style="rounded=0;whiteSpace=wrap;html=1;fillColor=#2A7AE2;fontColor=#ffffff;strokeColor=#000000;" vertex="1" parent="1">
          <mxGeometry x="240" y="40" width="140" height="36" as="geometry"/>
        </mxCell>

        <mxCell id="e_tipoanim" value="TIPOANIM" style="rounded=0;whiteSpace=wrap;html=1;fillColor=#2A7AE2;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="520" y="20" width="120" height="36" as="geometry"/>
        </mxCell>

        <mxCell id="e_raza" value="RAZA" style="rounded=0;whiteSpace=wrap;html=1;fillColor=#2A7AE2;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="520" y="120" width="120" height="36" as="geometry"/>
        </mxCell>

        <mxCell id="e_dueno" value="DUEÑO" style="rounded=0;whiteSpace=wrap;html=1;fillColor=#2A7AE2;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="80" y="180" width="120" height="36" as="geometry"/>
        </mxCell>

        <mxCell id="e_veterinario" value="VETERINARIO" style="rounded=0;whiteSpace=wrap;html=1;fillColor=#2A7AE2;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="260" y="220" width="140" height="36" as="geometry"/>
        </mxCell>

        <mxCell id="e_hclinica" value="HCLINICA" style="rounded=0;whiteSpace=wrap;html=1;fillColor=#A3D48B;fontColor=#000000;" vertex="1" parent="1">
          <mxGeometry x="60" y="300" width="120" height="36" as="geometry"/>
        </mxCell>

        <mxCell id="e_serciop" value="SERCIOP" style="rounded=0;whiteSpace=wrap;html=1;fillColor=#6FBF73;fontColor=#000000;" vertex="1" parent="1">
          <mxGeometry x="420" y="260" width="120" height="36" as="geometry"/>
        </mxCell>

        <mxCell id="e_servicio" value="SERVICIO" style="rounded=0;whiteSpace=wrap;html=1;fillColor=#2A7AE2;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="620" y="260" width="120" height="36" as="geometry"/>
        </mxCell>

        <!-- Attributes PACIENTE -->
        <mxCell id="a_idpaciente" value="idpaciente" style="ellipse;whiteSpace=wrap;html=1;fillColor=#a80000;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="160" y="24" width="80" height="28" as="geometry"/>
        </mxCell>
        <mxCell id="a_nom_pac" value="nom" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f7d154;" vertex="1" parent="1">
          <mxGeometry x="240" y="-4" width="60" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_edad" value="edad" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f7d154;" vertex="1" parent="1">
          <mxGeometry x="320" y="-4" width="60" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_sexo" value="sexo" style="ellipse;whiteSpace=wrap;html=1;fillColor=#8e44ad;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="320" y="80" width="70" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_tamano" value="tamaño" style="ellipse;whiteSpace=wrap;html=1;fillColor=#8e44ad;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="160" y="80" width="70" height="26" as="geometry"/>
        </mxCell>

        <!-- Sub-attributes sexo -->
        <mxCell id="a_hembra" value="hembra" style="ellipse;whiteSpace=wrap;html=1;fillColor=#a3a3ff;" vertex="1" parent="1">
          <mxGeometry x="400" y="80" width="60" height="22" as="geometry"/>
        </mxCell>
        <mxCell id="a_macho" value="macho" style="ellipse;whiteSpace=wrap;html=1;fillColor=#a3a3ff;" vertex="1" parent="1">
          <mxGeometry x="400" y="108" width="60" height="22" as="geometry"/>
        </mxCell>

        <!-- Sub-attributes tamaño -->
        <mxCell id="a_pequeno" value="pequeño" style="ellipse;whiteSpace=wrap;html=1;fillColor=#7f7fff;" vertex="1" parent="1">
          <mxGeometry x="80" y="80" width="64" height="22" as="geometry"/>
        </mxCell>
        <mxCell id="a_mediano" value="mediano" style="ellipse;whiteSpace=wrap;html=1;fillColor=#7f7fff;" vertex="1" parent="1">
          <mxGeometry x="80" y="108" width="64" height="22" as="geometry"/>
        </mxCell>
        <mxCell id="a_grande" value="grande" style="ellipse;whiteSpace=wrap;html=1;fillColor=#7f7fff;" vertex="1" parent="1">
          <mxGeometry x="80" y="136" width="64" height="22" as="geometry"/>
        </mxCell>

        <!-- Attributes DUEÑO -->
        <mxCell id="a_iddueno" value="iddueño" style="ellipse;whiteSpace=wrap;html=1;fillColor=#a80000;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="24" y="164" width="80" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_nom_due" value="nom" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f7d154;" vertex="1" parent="1">
          <mxGeometry x="24" y="200" width="64" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_dni" value="dni" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f7d154;" vertex="1" parent="1">
          <mxGeometry x="24" y="236" width="64" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_tel" value="tel" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f7d154;" vertex="1" parent="1">
          <mxGeometry x="120" y="236" width="64" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_correo" value="correo" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f7d154;" vertex="1" parent="1">
          <mxGeometry x="24" y="272" width="80" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_dir" value="dir" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f7d154;" vertex="1" parent="1">
          <mxGeometry x="120" y="272" width="64" height="26" as="geometry"/>
        </mxCell>

        <!-- Attributes VETERINARIO -->
        <mxCell id="a_idvet" value="idveterinario" style="ellipse;whiteSpace=wrap;html=1;fillColor=#a80000;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="240" y="188" width="110" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_nomveter" value="nomveterina" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f7d154;" vertex="1" parent="1">
          <mxGeometry x="240" y="244" width="110" height="26" as="geometry"/>
        </mxCell>

        <!-- Attributes HCLINICA -->
        <mxCell id="a_idhclinica" value="idhclinica" style="ellipse;whiteSpace=wrap;html=1;fillColor=#a80000;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="-16" y="300" width="100" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_fecha_hc" value="fecha" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f7d154;" vertex="1" parent="1">
          <mxGeometry x="24" y="340" width="64" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_diagnostico" value="diagnostico" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f7d154;" vertex="1" parent="1">
          <mxGeometry x="120" y="340" width="84" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_tratamiento" value="tratamiento" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f7d154;" vertex="1" parent="1">
          <mxGeometry x="24" y="380" width="84" height="26" as="geometry"/>
        </mxCell>

        <!-- Attributes SERVICIO & SERCIOP -->
        <mxCell id="a_idservicio" value="idservicio" style="ellipse;whiteSpace=wrap;html=1;fillColor=#a80000;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="620" y="220" width="84" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_nom_serv" value="nom" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f7d154;" vertex="1" parent="1">
          <mxGeometry x="620" y="188" width="64" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_valor_serv" value="valor" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f7d154;" vertex="1" parent="1">
          <mxGeometry x="700" y="188" width="64" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_idserciop" value="idserciop" style="ellipse;whiteSpace=wrap;html=1;fillColor=#a80000;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="420" y="320" width="84" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_fecha_ser" value="fecha" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f7d154;" vertex="1" parent="1">
          <mxGeometry x="420" y="360" width="64" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_valor_serciop" value="valor" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f7d154;" vertex="1" parent="1">
          <mxGeometry x="500" y="360" width="64" height="26" as="geometry"/>
        </mxCell>

        <!-- Attributes TIPOANIM & RAZA -->
        <mxCell id="a_idtipoanim" value="idtipoanim" style="ellipse;whiteSpace=wrap;html=1;fillColor=#a80000;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="520" y="-12" width="84" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_nom_tipo" value="nom" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f7d154;" vertex="1" parent="1">
          <mxGeometry x="620" y="-12" width="64" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_idraza" value="idraza" style="ellipse;whiteSpace=wrap;html=1;fillColor=#a80000;fontColor=#ffffff;" vertex="1" parent="1">
          <mxGeometry x="620" y="120" width="84" height="26" as="geometry"/>
        </mxCell>
        <mxCell id="a_nomraza" value="nomraza" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f7d154;" vertex="1" parent="1">
          <mxGeometry x="620" y="152" width="84" height="26" as="geometry"/>
        </mxCell>

        <!-- Relationships (edges) -->
        <mxCell id="r_pac_id" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="e_paciente" target="a_idpaciente">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="r_pac_nom" style="edgeStyle=orthogonalEdgeStyle;html=1;" edge="1" parent="1" source="e_paciente" target="a_nom_pac">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="r_pac_edad" style="edgeStyle=orthogonalEdgeStyle;html=1;" edge="1" parent="1" source="e_paciente" target="a_edad">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="r_pac_sexo" style="edgeStyle=orthogonalEdgeStyle;html=1;" edge="1" parent="1" source="e_paciente" target="a_sexo">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="r_sexo_hembra" style="edgeStyle=orthogonalEdgeStyle;html=1;" edge="1" parent="1" source="a_sexo" target="a_hembra">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="r_sexo_macho" style="edgeStyle=orthogonalEdgeStyle;html=1;" edge="1" parent="1" source="a_sexo" target="a_macho">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="r_pac_tamano" style="edgeStyle=orthogonalEdgeStyle;html=1;" edge="1" parent="1" source="e_paciente" target="a_tamano">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="r_tamano_peq" style="edgeStyle=orthogonalEdgeStyle;html=1;" edge="1" parent="1" source="a_tamano" target="a_pequeno">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="r_tamano_med" style="edgeStyle=orthogonalEdgeStyle;html=1;" edge="1" parent="1" source="a_tamano" target="a_mediano">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="r_tamano_gra" style="edgeStyle=orthogonalEdgeStyle;html=1;" edge="1" parent="1" source="a_tamano" target="a_grande">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <!-- Entity relationships -->
        <mxCell id="r_pac_tipo" style="edgeStyle=orthogonalEdgeStyle;html=1;" edge="1" parent="1" source="e_paciente" target="e_tipoanim">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="r_pac_raza" style="edgeStyle=orthogonalEdgeStyle;html=1;" edge="1" parent="1" source="e_paciente" target="e_raza">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="r_pac_dueno" style="edgeStyle=orthogonalEdgeStyle;html=1;" edge="1" parent="1" source="e_paciente" target="e_dueno">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="r_pac_vet" style="edgeStyle=orthogonalEdgeStyle;html=1;" edge="1" parent="1" source="e_paciente" target="e_veterinario">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="r_vet_hclinica" style="edgeStyle=orthogonalEdgeStyle;html=1;" edge="1" parent="1" source="e_veterinario" target="e_hclinica">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <mxCell id="r_serciop_servicio" style="edgeStyle=orthogonalEdgeStyle;html=1;" edge="1" parent="1" source="e_serciop" target="e_servicio">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
        <mxCell id="r_pac_serciop" style="edgeStyle=orthogonalEdgeStyle;html=1;" edge="1" parent="1" source="e_paciente" target="e_serciop">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>

        <!-- edge labels for cardinality (simple text nodes) -->
        <mxCell id="lbl_pac_tipo" value="N" style="text;html=1;strokeColor=none;fillColor=none;fontColor=#000000;" vertex="1" parent="1">
          <mxGeometry x="420" y="28" width="16" height="16" as="geometry"/>
        </mxCell>

        <mxCell id="lbl_tipo" value="1" style="text;html=1;strokeColor=none;fillColor=none;fontColor=#000000;" vertex="1" parent="1">
          <mxGeometry x="548" y="28" width="16" height="16" as="geometry"/>
        </mxCell>

      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
