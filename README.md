# rspec yasnippets

## Installation

I am assuming you have yasnippets installed.

    (yas-load-directory "<your location>/yasnippets-rspec/rspec-snippets")

## Information

* For information on yasnippets see https://github.com/capitaomorte/yasnippet
* For information on rSpec see http://rspec.info

## Contents

- rspec-snippets: the actual directory of snippets


## Differences from the TextMate versions:

* Controller snippets, describe blocks, matcher gain {lead,trail}ing newline
* RESTful controller dropdown order is natural (vs. GET|POST|PUT|DELETE)
* it block handling broken into "it" for the block form and "itd" for a
  one line form
* mock_with snippet order is natural (vs. mocha|flexmock|rr)
* should{,_not} be_instance_of snippet shortcuts changed shbio and
  shnbio for consistency
* dropped 'shkof' for should_not be_kind_of, opting for the more
  consistent shnbko
* should{,_not} eq{ua}l matcher order is now natural
* should{_not} {match,=~} order is now natural
* should_{redirect,render,respond} order is now natural
