INSERT INTO
  oauth_client_details (
    client_id,
    client_secret,
    resource_ids,
    scope,
    authorized_grant_types,
    access_token_validity,
    refresh_token_validity
  )
VALUES
  (
    'client1',
    'secret1',
    'user',
    'read',
    'authorization_code,check_token,refresh_token,password',
    1000000,
    1000000
  );