# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

if ENV['CI'] == true
    gem 'danger-checkstyle_reports'
else
    gem 'danger-checkstyle_reports', path: '../danger-checkstyle_reports'
end

gem 'pry'