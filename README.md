[![Run Ubuntu](https://github.com/gridai-actions/gridai-run/actions/workflows/unittest-ubuntu.yml/badge.svg)](https://github.com/gridai-actions/gridai-run/actions/workflows/unittest-ubuntu.yml) 
[![Run Mac](https://github.com/gridai-actions/gridai-run/actions/workflows/unittest-mac.yml/badge.svg)](https://github.com/gridai-actions/gridai-run/actions/workflows/unittest-mac.yml) 
[![Run Win](https://github.com/gridai-actions/gridai-run/actions/workflows/unittest-win.yml/badge.svg)](https://github.com/gridai-actions/gridai-run/actions/workflows/unittest-win.yml)

Run on Grid.ai and download artifacts on success.  

# Overview

This action performs the following:
- Run specified script
- Wait for success status
- Download artifacts


```
gridai.py cli "grid run --ignore_warnings hello.py" status_to_kv --gha True
gridai.py run messy-bhabha-6326
  def run(self, obj_id:str, obj_status_expr="succeeded|cancelled|failed|stopped", id_is_expr=False, obj_id_col:str="run" , obj_status_col:str="status"):
