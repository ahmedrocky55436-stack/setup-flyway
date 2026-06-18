#            - name: Setup Redgate Flyway
  # You may pin to the exact commit or the version.
  # uses: red-gate/setup-flyway@e4690eb661a3d0f33ec35728df2228358e5b6f0c
  uses: red-gate/setup-flyway@v3.3.0
  with:
    # The version specification
    version: # optional, default is latest
    # The Flyway edition to use. Must be one of 'community', 'teams', or 'enterprise'.
    edition: 
    # Confirm you consent to the EULA found at https://www.red-gate.com/eula.
    i-agree-to-the-eula: 
    # The target platform architecture. Defaults to the current platform's architecture.
    architecture: # optional
    # The target OS platform. Defaults to the current platform.
    platform: # optional
    # A Redgate email to be used in conjunction with the token parameter to configure a personal access token (PAT). Used to authenticate Flyway to use either Teams or Enterprise.
    email: # optional
    # A personal access token (PAT) to be used in conjunction with the email configuration parameter. This is used to license Flyway to access Teams or Enterprise features.
    token: # optional
    # The maximum number of times to attempt authenticating Flyway. Defaults to 2.
    max-auth-attempts: # optional, default is 2
    # Remove older versions of Flyway from the tool cache on self-hosted runners.
    clean-old-cached-versions: # optional, default is true

          
