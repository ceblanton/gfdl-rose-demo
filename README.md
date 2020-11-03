# template-repository
Repository template for GFDL-NOAA organization

# Start suite
rose suite-run

# Start cylc GUI
cylc gui gfdl-rose-demo

# Restart from stopped; reload suite
rose suite-run --restart

# Restart from stopped; don't reload suite
rose suite-restart

# Restart while running: reload suite
rose suite-run --reload

# Restart while running; don't reload suite
cylc stop gfdl-rose-demo --now --now
rose suite-restart
