opts = {
  access_key_id:ENV['AWS_ACCESS_KEY_ID'],
  secret_access_key:ENV['AWS_SECRET_KEY'],
  bucket:"naohta-shops",
  :s3_permissions => :public_read
}
p opts

guard 's3', opts do
  watch(/.*/)
end
