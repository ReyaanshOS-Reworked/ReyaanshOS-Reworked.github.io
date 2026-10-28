# Add a Device

This is a maintainer guide. It is stored in `Templates/` and is not
published on the website.

## Where to add devices

Edit `docs/devices/index.md`.

The public page should contain device entries only. Do not put this
guide, setup instructions, compatibility reports, troubleshooting,
or "What works" sections on the Devices page.

## Entry design

Use a vendor section and a styled entry for each device. Example:

    <div class="device-vendor">
      <h2>Nokia</h2>
      <div class="device-list">
        <div class="device-entry">
          <div>
            <div class="device-codename">pl2</div>
            <div class="device-name">Nokia 6.1</div>
          </div>
        </div>
      </div>
    </div>

The `device-vendor`, `device-list`, `device-entry`, `device-codename`,
and `device-name` classes are intended for the directory styling.

Only add actual devices when you decide to list them. The rebuilt
Devices page starts empty.
