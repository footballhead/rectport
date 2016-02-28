# Rectangular Portals

Rectangular portals for Portal in DX9.

## Required Tools

  * Portal's `vpk.exe` (should come with Portal)
  * Synfig
  * VTFEdit

## Installing

 1. Run `make_vpk.bat`
 2. Copy resulting `rectport.vpk` to `steamapps/common/portal/portal/custom/`
  
## Files

### Files for Blue Portal

  * `portal_blue_open.png`: static portal frame texture
  * `portal_blue_double.png`: closed portal texture; double the height
  * `blue_closed_anim.sifz`: Synfig animation for closed portal
  * `rectport/materials/models/portals/portal_blue_open.vtf`
  * `rectport/materials/models/portals/portal_blue_closed.vtf`

### Files for Red Portal

  * `portal_red_open.png`: static portal frame texture
  * `portal_orange_double.png`: closed portal texture; double the height
  * `orange_closed_anim.sifz`: Synfig animation for closed portal
  * `rectport/materials/models/portals/portal_red_open.vtf`
  * `rectport/materials/models/portals/portal_red_closed.vtf`
  
### Particles

The particles in `rectport/particles/` are modified portal particle systems which look better.
  
## Editing
  
### Modifying Portal Frame

 1. Edit frame PNG with your favourite image editor
 2. Fire up VTFEdit
 3. File -> Import
 4. Save VTF to `rectport/materials/models/portals/`
 
### Modifying Closed Portal

 1. Edit closed portal PNG with image editor
 2. Open corresponding Synfig animation
 3. File -> Render
 4. Make sure saving to PNG, then click Render
 5. Fire up VTFEdit
 6. File -> Import
 7. Select all exported frames in order
 8. Save VTF to `rectport/materials/models/portals/`
 
