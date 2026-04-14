# atlas_gui

GUI for the Design Engineering Atlas knowledge graph.

## data contract

Read-only access to ../atlas_pipeline/pipeline_v2/database.db.
Do not modify the database.
Do not move the database.
The pipeline that produced this data lives in ../atlas_pipeline/pipeline_v2/.

## status

Prototype implemented in `preview.html` (single-file D3, no build step).
Export pipeline implemented in `export_graph.py`, outputting `graph_data.json`.
This prototype is a design/interaction reference and not final production app code.
See `PRD.md` for source-of-truth requirements.

## to start building

Read ../ARCHITECTURE.md section 6 first.
Then read ../atlas_pipeline/pipeline_v2/AUDIT.md for database schema.
Then validate behavior against `preview.html` + `PRD.md` before scaffolding React.
