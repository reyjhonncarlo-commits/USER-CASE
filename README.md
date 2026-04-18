# USER-CASE

<mxfile host="app.diagrams.net" modified="2024-03-20T00:00:00.000Z" agent="Gemini" version="21.0.0" type="device">
  <diagram id="ChronoQuestDiagram" name="ChronoQuest Use Case">
    <mxGraphModel dx="1422" dy="798" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="boundary" value="ChronoQuest System" style="shape=rect;html=1;verticalAlign=top;fontStyle=1;whiteSpace=wrap;align=center;" vertex="1" parent="1">
          <mxGeometry x="200" y="40" width="400" height="720" as="geometry" />
        </mxCell>
        <mxCell id="student" value="Student" style="shape=umlActor;verticalLabelPosition=bottom;verticalAlign=top;html=1;" vertex="1" parent="1">
          <mxGeometry x="80" y="300" width="30" height="60" as="geometry" />
        </mxCell>
        <mxCell id="teacher" value="Teacher" style="shape=umlActor;verticalLabelPosition=bottom;verticalAlign=top;html=1;" vertex="1" parent="1">
          <mxGeometry x="720" y="450" width="30" height="60" as="geometry" />
        </mxCell>
        <mxCell id="admin" value="Administrator" style="shape=umlActor;verticalLabelPosition=bottom;verticalAlign=top;html=1;" vertex="1" parent="1">
          <mxGeometry x="720" y="100" width="30" height="60" as="geometry" />
        </mxCell>
        <mxCell id="uc_login" value="Login" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="340" y="80" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="uc_register" value="Register / Join Class" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="230" y="240" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="uc_play" value="Play Historical Quest" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="230" y="340" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="uc_sync" value="Sync Progress" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="230" y="480" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="uc_view" value="View Student Performance" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="450" y="400" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="uc_class" value="Manage Class" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="450" y="240" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="uc_quiz" value="Manage Quiz Content" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="450" y="320" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="uc_admin_manage" value="Manage Teacher Accounts" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="340" y="650" width="140" height="70" as="geometry" />
        </mxCell>
        <mxCell id="line1" source="student" target="uc_register" style="endArrow=none;html=1;" edge="1" parent="1" />
        <mxCell id="line2" source="student" target="uc_play" style="endArrow=none;html=1;" edge="1" parent="1" />
        <mxCell id="line3" source="student" target="uc_sync" style="endArrow=none;html=1;" edge="1" parent="1" />
        <mxCell id="line4" source="teacher" target="uc_view" style="endArrow=none;html=1;" edge="1" parent="1" />
        <mxCell id="line5" source="teacher" target="uc_class" style="endArrow=none;html=1;" edge="1" parent="1" />
        <mxCell id="line6" source="teacher" target="uc_quiz" style="endArrow=none;html=1;" edge="1" parent="1" />
        <mxCell id="line7" source="admin" target="uc_admin_manage" style="endArrow=none;html=1;" edge="1" parent="1" />
        <mxCell id="gen1" source="admin" target="teacher" style="endArrow=block;endFill=0;edgeStyle=orthogonalEdgeStyle;html=1;" edge="1" parent="1" />
        <mxCell id="inc1" source="uc_register" target="uc_login" style="endArrow=open;dashed=1;html=1;endFill=0;labelBackgroundColor=none;" edge="1" parent="1">
          <mxCell key="value" value="&lt;&lt;include&gt;&gt;" style="edgeLabel;resizable=0;html=1;align=center;verticalAlign=middle;" connectable="0" vertex="1" />
        </mxCell>
        <mxCell id="inc2" source="uc_class" target="uc_login" style="endArrow=open;dashed=1;html=1;endFill=0;labelBackgroundColor=none;" edge="1" parent="1">
          <mxCell key="value" value="&lt;&lt;include&gt;&gt;" style="edgeLabel;resizable=0;html=1;align=center;verticalAlign=middle;" connectable="0" vertex="1" />
        </mxCell>
        <mxCell id="inc3" source="uc_quiz" target="uc_login" style="endArrow=open;dashed=1;html=1;endFill=0;labelBackgroundColor=none;" edge="1" parent="1">
          <mxCell key="value" value="&lt;&lt;include&gt;&gt;" style="edgeLabel;resizable=0;html=1;align=center;verticalAlign=middle;" connectable="0" vertex="1" />
        </mxCell>
        <mxCell id="ext1" source="uc_sync" target="uc_play" style="endArrow=open;dashed=1;html=1;endFill=0;labelBackgroundColor=none;" edge="1" parent="1">
          <mxCell key="value" value="&lt;&lt;extend&gt;&gt;" style="edgeLabel;resizable=0;html=1;align=center;verticalAlign=middle;" connectable="0" vertex="1" />
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
